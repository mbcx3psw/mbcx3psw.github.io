---
layout: page
title: Family History
permalink: /familyHistory/

---
During the lockdown I started to research my family tree. It's been a lot of fun and I've learnt a lot.

These articles are interesting things I've found out about my family that I'd like to document.


## Articles

{% for page in site.familyHistory %}
  <a href="{{ page.url }}">{{ page.title }}</a>
{% endfor %}
