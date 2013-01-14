---
layout: page
title: iamggreen
tagline: Supporting tagline
---
{% include JB/setup %}

#I'm Moving...

Please be patient as I move this site from WordPress to GitHub Pages.

---

<br/>
<div id="posts">
  <h2>Blog Posts</h2>
  <ul>
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> - <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
