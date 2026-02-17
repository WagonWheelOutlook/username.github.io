---
layout: default
title: Home
---

<h1>My Blog Posts</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      <span>({{ post.date | date: "%B %d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>
