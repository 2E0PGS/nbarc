---
title: Lighthouses on the air
date: 2019-08-17 07:21:19
author: Peter Stevenson
categories: events
---

{% include main-template.md %}

# Lighthoues on the air

{% for image in site.static_files reversed %}{% if image.path contains 'assets/2019-08-17' %}<img src="{{ site.baseurl }}{{ image.path }}" alt="image"/><br/>{% endif %}{% endfor %}