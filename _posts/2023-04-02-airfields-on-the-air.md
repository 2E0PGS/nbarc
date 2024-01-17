---
title: Airfields on the air
date: 2023-04-02 07:21:19
author: Peter Stevenson
categories: events
---

{% include main-template.md %}

# Airfields on the air

{% for image in site.static_files reversed %}{% if image.path contains 'assets/2023-04-02' %}<img src="{{ site.baseurl }}{{ image.path }}" alt="image"/><br/>{% endif %}{% endfor %}