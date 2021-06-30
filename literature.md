---
title: Literature
description: Literature
nav: true
---

{% include main-template.md %}

# Literature

## Articles

### Ashton Windmills On The Air (11th - 12th May 2019)

> by Rocky (M6VRL)

<a href="{{ site.baseurl }}/assets/articles/ashton-windmill.pdf" target="_blank">ashton-windmill.pdf</a>

### DMR radio guide

> by Yaesu

<a href="{{ site.baseurl }}/assets/articles/digitalcommunicationsguide-e1.pdf" target="_blank">digitalcommunicationsguide-e1.pdf</a>

## Talks

### IP and COM ports for amateur radio (October 2019)

> by Peter Stevenson (2E0PGS)

<a href="{{ site.baseurl }}/assets/articles/2019-ip-and-com-ports-for-radio/ip-and-com-ports-for-radio-animated.pdf" target="_blank">ip-and-com-ports-for-radio-animated.pdf</a> | <a href="{{ site.baseurl }}/assets/articles/2019-ip-and-com-ports-for-radio/ip-and-com-ports-for-radio-animated.odp" target="_blank">ip-and-com-ports-for-radio-animated.odp</a>

### VSWR lecture (March 2018)

> by Dennis Buchan (M6EZX)

<a href="{{ site.baseurl }}/assets/articles/2018-vswr-lecture/vswr-lecture.pdf" target="_blank">vswr-lecture.pdf</a> | <a href="{{ site.baseurl }}/assets/articles/2018-vswr-lecture/vswr-lecture.pptx" target="_blank">vswr-lecture.pptx</a> | <a href="{{ site.baseurl }}/assets/articles/2018-vswr-lecture/vswr-lecture-ladder-diagram.xlsx" target="_blank">vswr-lecture-ladder-diagram.xlsx</a>

## Q5

Our Q5 newsletter sorted newest at the top.

{% for q5 in site.static_files reversed %}{% if q5.path contains 'q5/collection' %}<a href="{{ site.baseurl }}{{ q5.path }}" target="_blank">{{ q5.name }}</a><br/>{% endif %}{% endfor %}

## Programme

Our club programme sorted newest at the top.

{% for programme in site.static_files reversed %}{% if programme.path contains 'programme/collection' %}<a href="{{ site.baseurl }}{{ programme.path }}" target="_blank">{{ programme.name }}</a><br/>{% endif %}{% endfor %}