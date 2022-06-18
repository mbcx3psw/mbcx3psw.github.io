---
layout: page
title: Family History
permalink: /Family-History/
doctype: history

---
During the lockdown I started to research my family tree. It's been a lot of fun and I've learnt a lot.

I've found that reading about family history can be pretty dry no matter how thrilling the underlying story. For me the exciting part of family history is when I make a discovery or uncover something unexpected. While I want to use this website as an opportunity to document what I've found out about my family I also want to convey the process I went through and some of the excitement I felt when I found out something new.


## Articles

{% for page in site.familyHistory %}
  <a href="{{ page.url }}">{{ page.title }}</a>
{% endfor %}
