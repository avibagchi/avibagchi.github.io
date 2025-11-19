---
title: ""
layout: page
sitemap: false
permalink: /blogs/
---

<style>
.post-header,
header.post-header,
h1.post-title {
  display: none !important;
}
</style>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title}}</a>
    </li>
  {% endfor %}
</ul>
