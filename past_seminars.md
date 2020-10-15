---
title: "The S³ seminars"
layout: blog
collectionpage: seminars
---

{% assign sorted = site.seminars | sort: 'date' | reverse %}

{% assign semsByYear =
    sorted | group_by_exp:"sem", "sem.date | date: '%Y'" %}

{% for year in semsByYear %}
<h2>{{ year.name }}</h2>
{% for sem in year.items %}
{% capture nowunix %}{{ 'now' | date: '%s' }}{% endcapture %}
{% capture semtime %}{{ sem.date | date: '%s' }}{% endcapture %}
{% if semtime <= nowunix %}
<h6><a href="{{ sem.url }}">{{ sem.title }}</a></h6>
{% if sem.perso != nil and sem.perso != "None" %}
<em><a href="{{ sem.perso }}">{{ sem.speaker }}</a></em> ({{ sem.affiliation }})
{% else %}
<i>{{ sem.speaker }}</i> ({{ sem.affiliation }})
{% endif %}<br/>
{{ sem.date | date: '%B %d, %Y — %H:%M' }} — {% if sem.online != nil %} Location: <a href="{{ sem.online }}">Online</a> {% elsif sem.location != nil %} Location: {{ sem.location }} {% endif %}
<hr/>
{% endif %}
{% endfor %}
{% endfor %}


