---
title: Pictures
description: Pictures etc
nav: true
---

{% include nav.md %}

# Pictures

{% for image in site.static_files %}{% if image.path contains 'images/collection' %}<img src="{{ site.baseurl }}{{ image.path }}" alt="image" />{% endif %}{% endfor %}
