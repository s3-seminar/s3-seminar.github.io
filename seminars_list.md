---
title: "The S³ seminars"
layout: blog
collectionpage: seminars
---

{% for post in site.seminars %}
<ul>
  <li>{{ post.speaker }} ({{ post.affiliation }}) <br/> {{ post.date | date: '%B %d, %Y' }} <br/> <a href="{{ post.url }}">{{ post.title }}</a></li>
</ul>
{% endfor %}
