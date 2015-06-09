---
layout: page
title: Bugsbunny8 Tech Sites
tagline: 
---
{% include JB/setup %}

# Self Introduction

A Tech Fans Blogging and pages, for tech records & discussion.

If u are interested, please check [In detail](introduction.html)

---

# Blog Series

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

---

# Projects

---

# To-Do


