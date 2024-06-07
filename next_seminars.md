---
title: "The next S³ seminars"
layout: blog
feature_image: "https://source.unsplash.com/w2JtIQQXoRU"
---

The S³ seminar is taking a summer break.
It will return in September at the start of the new academic year.

{% assign sorted = site.seminars | sort: 'date' %}

{% for sem in sorted %}
{% capture nowunix %}{{ 'now' | date: '%s' }}{% endcapture %}
{% capture semtime %}{{ sem.date | date: '%s' }}{% endcapture %}
{% if semtime > nowunix %}
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
