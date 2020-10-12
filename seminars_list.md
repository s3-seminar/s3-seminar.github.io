---
title: "The S³ seminars"
layout: blog
collectionpage: seminars
---

{% for post in site.seminars %}
<ul>
  <li> {% if post.url != nil %}
          <a href="{{ post.url }}">{{ post.speaker }}</a> ({{ post.affiliation }})
        {% else %}
          {{ post.speaker }} ({{ post.affiliation }})
        {% endif %} <br/>
  
   {{ post.date | date: '%B %d, %Y — %H:%M' }} —
        {% if post.online != nil %}
          Location: <a href="{{ post.online }}">Online</a>
        {% elsif post.location != nil %}
          Location: {{ post.location }}
        {% endif %}<br/>
  <a href="{{ post.url }}">{{ post.title }}</a></li>
</ul>
{% endfor %}
