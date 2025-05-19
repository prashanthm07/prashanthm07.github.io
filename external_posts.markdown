---
layout: default
title: External Posts
permalink: /external-posts/
---
<ul>
  {% for post in site.external_posts %}
    <li>
      <a href="{{ post.external_url }}" target="_blank">{{ post.title }}</a> —
      <small>{{ post.date | date: "%b %d, %Y" }} on {{ post.platform }}</small>
    </li>
  {% endfor %}
</ul>
