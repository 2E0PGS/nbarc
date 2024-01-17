---
title: Events
description: Club events
nav: true
---

{% include main-template.md %}

Log of previous club events and field days.

<ul>
  {% for post in site.posts %}
    {% if post.archived != true %}
      <li>
        {{ post.date | date: "%Y-%m-%d" }} <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>
