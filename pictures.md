---
title: Pictures
description: Club photos
nav: true
---

{% include main-template.md %}

# Club photos

For older photos see the archive: [Picture archive]()

## Gallery

{% for image in site.static_files %}{% if image.path contains 'images/collection' %}<img src="{{ site.baseurl }}{{ image.path }}" alt="image" height="400px" width="auto"/><br/>{% endif %}{% endfor %}
