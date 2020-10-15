---
title: "The S³ seminars"
layout: blog
collectionpage: seminars
---

{% assign sorted = site.seminars | sort: 'date' | reverse %}

{% for post in sorted %}
<ul>
  <li> <b><a href="{{ post.url }}">{{ post.title }}</a></b><br/>
  {% if post.url != nil %}
    <a href="{{ post.perso }}">{{ post.speaker }}</a> ({{ post.affiliation }})
  {% else %}
    {{ post.speaker }} ({{ post.affiliation }})
  {% endif %} <br/>
  {{ post.date | date: '%B %d, %Y — %H:%M' }} —
  {% if post.online != nil %}
    Location: <a href="{{ post.online }}">Online</a>
  {% elsif post.location != nil %}
    Location: {{ post.location }}
  {% endif %}</li>
</ul>
{% endfor %}
