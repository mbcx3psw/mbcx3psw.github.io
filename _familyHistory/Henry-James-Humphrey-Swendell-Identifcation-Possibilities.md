---
layout: page
title: Identifying Henry James Humphrey Swendell - Possibilities.
permalink: /swendell/Identifying-Henry-James-Humphrey-Swendell-Possibilities
doctype: history
tag: HJHS
---

I've <a href="/swendell/Serjeants-Mess-Portrait-Listing">separated all of the pictures from the serjeants' mess portrait</a> to get a clearer picture of each individual.

Working on the basis that Henry was in possession of the British and Turkish Crimean medals when the photo was taken in 1868 he's in one of the pictures below.

<div class="columns image">
{% for serjeant in site.data.serjeants %}
{% if serjeant.noOfMedals == 2 %}
 <img height="256" src="/images/serjeantsMess/SerjeantsMess_{{serjeant.number}}.jpg" alt="{{serjeant.number}}" title="Number: {{serjeant.number}}">
{% endif %}
{% endfor %}
</div>
