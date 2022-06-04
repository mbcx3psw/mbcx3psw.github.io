---
layout: default
Title: Work
permalink: /work/
---

I’ve been involved in the delivery of enterprise software for over 20 years. In that time I’ve worked as a developer, analyst, project manager and product owner. I've experienced different approaches and methodologies over the years as well as encountering lots of indviduals and their differing perspectives on how to work. 

These articles are my thoughts on how best to work in an enterprise software environment when you're responsible for delivery.

## Articles


{% for page in site.work %}
<a href="{{ page.url }}">{{ page.title }}</a>
{% endfor %}
