---
layout: page
title: "Tags"
permalink: /tags/
---

<h2>All Tags</h2>

<ul>
  {% for tag in site.tags %}
    <li>{{ tag[0] }} ({{ tag[1].size }})</li>
  {% endfor %}
</ul>
