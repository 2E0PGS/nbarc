---
title: Pictures
description: Club photos
nav: true
---

{% include main-template.md %}

# Club photos

## Gallery of our new club venue

{% for image in site.static_files reversed %}{% if image.path contains 'images/collection' %}<img src="{{ site.baseurl }}{{ image.path }}" alt="image"/><br/>{% endif %}{% endfor %}

Further images of events are under the [events](posts.md) section

## 2018 AGM 

![2018-club-photo-agm.jpg](/assets/images/2018-club-photo-agm.jpg)

## Circa 1990 AGM

![1990-club-photo-circa.jpg](/assets/images/1990-club-photo-circa.jpg)

## Older

For older photos see the archive: [Picture archive](https://nbarc.weebly.com/picture-archive.html){:target="_blank"}