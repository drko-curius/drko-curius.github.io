---
layout: archive
permalink: /books/
title: "Books"
author_profile: true
---

{% raw %}{% assign books = site.books | sort: 'date' | reverse %}

{% for book in books %}
  <h2><a href="{{ book.url }}">{{ book.title }}</a></h2>
  <p>{{ book.excerpt }}</p>
  <hr/>
{% endfor %}{% endraw %}
