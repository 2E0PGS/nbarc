---
title: Literature
description: Literature
nav: true
---

{% include nav.md %}

# Literature

## Latest club programme

TBA

## Articles

TBA

## Talks

TBA

## Q5

Our newsletter sorted newest at the top.

{% for q5 in site.static_files reversed %}{% if q5.path contains 'q5/collection' %}<a href="{{ site.baseurl }}{{ q5.path }}">{{ q5.name }}</a><br/>{% endif %}{% endfor %}