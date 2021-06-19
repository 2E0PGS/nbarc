---
title: Literature
description: Literature
nav: true
---

{% include main-template.md %}

# Literature

## Latest club programme

TBA

## Articles

TBA

## Talks

TBA

## Q5

Our Q5 newsletter sorted newest at the top.

{% for q5 in site.static_files reversed %}{% if q5.path contains 'q5/collection' %}<a href="{{ site.baseurl }}{{ q5.path }}" target="_blank">{{ q5.name }}</a><br/>{% endif %}{% endfor %}

## Programme

Our club programme sorted newest at the top.

{% for programme in site.static_files reversed %}{% if programme.path contains 'programme/collection' %}<a href="{{ site.baseurl }}{{ programme.path }}" target="_blank">{{ programme.name }}</a><br/>{% endif %}{% endfor %}