---
title: Events
description: Club events
nav: false
---

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date }} <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


<ul>
  {% for page in site.static_files reversed %}{% if page.path contains 'events/' %}<a href="{{ site.baseurl }}{{ page.path }}">{{ page.title }}</a><br/>{% endif %}{% endfor %}
</ul>