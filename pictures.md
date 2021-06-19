---
title: Pictures
description: Club photos
nav: true
---

{% include main-template.md %}

# Club photos

For older photos see the archive: [Picture archive]()

| Circa 1990                                                                               | 2018 AGM                                                                             |
|------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| ![1990-club-photo-circa.jpg]({{ site.baseurl }}/assets/images/1990-club-photo-circa.jpg) | ![2018-club-photo-agm.jpg]({{ site.baseurl }}/assets/images/2018-club-photo-agm.jpg) |

## Gallery

{% for image in site.static_files %}{% if image.path contains 'images/collection' %}<img src="{{ site.baseurl }}{{ image.path }}" alt="image" height="400px" width="auto"/><br/>{% endif %}{% endfor %}
