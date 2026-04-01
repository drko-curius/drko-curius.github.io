---
layout: archive
permalink: /books/
collection: books
entries_layout: grid
title: "Book Reviews"
---

<ul>
{% for post in site.books reversed %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
