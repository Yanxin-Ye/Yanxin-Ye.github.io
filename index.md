---
layout: home
title: "Welcome"
---

<div style="text-align: center; margin-top: 50px;">

  <!-- Profile Picture -->
  <img src="/assets/nicole.jpg" alt="Yanxin (Nicole) Ye" style="width:200px; border-radius:50%; border:2px solid #007ACC; margin-bottom:20px;">

  <!-- Short Intro -->
  <h1>Hi, I'm Yanxin (Nicole) Ye</h1>
  <p>Senior Data Scientist | GenAI & Analytics </p>

  <p>
    I am a Senior Data Scientist, and I have also worked as a Software Engineer, Product Manager, and Data Analyst.  
    This cross-functional background gives me the opportunity to view a tech product from different angles.
  </p>

  <!-- About Me Button -->
  <a href="/about/" style="display:inline-block; padding: 15px 30px; margin-top:20px; background-color: #007ACC; color: white; border-radius: 5px; text-decoration: none; font-weight:bold;">
    About Me
  </a>


---


## 💻 Tech Blog

Here are some of my recent posts about AI and technology:

<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%b %-d, %Y" }}
    </li>
  {% endfor %}
</ul>

<p>
  <a href="/blog/" style="display:inline-block; padding: 10px 20px; margin-top:10px; background-color:#007ACC; color:white; border-radius:5px; text-decoration:none;">
    View All Posts
  </a>
</p>

</div>