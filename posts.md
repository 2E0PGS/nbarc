---
title: Events
description: Club events
nav: false
---

{% include main-template.md %}

Log of previous club events and field days.

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: "%Y-%m-%d" }} <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
