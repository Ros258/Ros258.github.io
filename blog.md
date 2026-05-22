---
layout: home
title: Blog
---

# My Blog

{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.date | date: "%B %d, %Y" }}</p>
    <p>{{ post.excerpt }}</p>
  </article>
{% endfor %}
