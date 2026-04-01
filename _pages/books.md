---
layout: collection
permalink: /books/
collection: books
entries_layout: grid
title: "Books"
---

{% for post in site.books %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
