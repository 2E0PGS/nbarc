---
title: Railways on the air
date: 2021-09-17 07:21:19
author: Peter Stevenson
categories: events
---

{% include main-template.md %}

# Railways on the air

{% for image in site.static_files reversed %}{% if image.path contains 'assets/2021-09-17' %}<img src="{{ site.baseurl }}{{ image.path }}" alt="image"/><br/>{% endif %}{% endfor %}