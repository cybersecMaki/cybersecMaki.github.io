---
layout: page
title: writeups
permalink: /writeups/
---


<h3> {{ tag[2] }} </h3>
<ul> 
  {% for post in tag
</ul>
{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}