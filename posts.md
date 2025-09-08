---
layout: page
title: "Posts"
permalink: /posts/
---

<nav style="margin-top:0.5rem">
  <a href="{{ site.baseurl }}/">Home</a> ·
  <a href="{{ site.baseurl }}/about/">About</a> ·
  <a href="{{ site.baseurl }}/research/">Research</a> ·
  <a href="{{ site.baseurl }}/posts/">Posts</a> ·
  <a href="{{ site.baseurl }}/hobbies/">Hobbies</a> ·
  <a href="mailto:EMAIL_HERE">Contact</a>
</nav>

Below are recent posts.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>— {{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

> Create new posts in the `_posts/` folder using the naming convention `YYYY-MM-DD-title.md`.
