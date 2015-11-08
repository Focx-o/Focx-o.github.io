---
layout: default
title: Search Page
---

<h1>Search Page</h1>
<hr/>

<form action="get" id="site_search">
  <label for="search_box">Search</label><input type="text" id="search_box">
  <input type="submit" value="search">
</form>

<ul id="results"></ul>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>