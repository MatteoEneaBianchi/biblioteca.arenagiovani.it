---
layout: page
title: Blog
lang: it
ref: 
permalink: /blog/
order: 2
img: https://www.dopara.it/cdn/shop/articles/come-conservare-libri-usati-consigli.jpg?v=1636232915
---
<h1>Tutti i Post</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
