---
layout: page
title: "Tech Blog"
permalink: /blog/
---

# Tech Blog

Welcome! Here are my latest posts about AI, data science, and technology:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%b %-d, %Y" }}
    </li>
  {% endfor %}
</ul>
