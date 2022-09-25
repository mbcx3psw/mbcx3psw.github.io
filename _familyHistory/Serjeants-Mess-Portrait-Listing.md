---
layout: page
title: Serjeants' Mess Portrait Listing.
permalink: /swendell/Serjeants-Mess-Portrait-Listing
doctype: history
tag: HJHS
---

This page is where I'll pull together my thoughts on the various portraits and who they may be.

Working on the basis that Henry was in possession of the British and Turkish Crimean medals when the photo was taken in 1868 he's in one of the pictures below.

<div class="columns image">
{% for serjeant in site.data.serjeants %}
{% if serjeant.noOfMedals == 2 %}
 <img height="256" src="/images/serjeantsMess/SerjeantsMess_{{serjeant.number}}.jpg" alt="{{serjeant.number}}" title="Number: {{serjeant.number}}">
{% endif %}
{% endfor %}
</div>

<h1> Portrait Listing and Key </h1>

<p align="center">
<img height="300" src="/images/serjeantsMess/170A12W_P_4636.jpg" alt="Faded image of 48 portraits arranged around the insigna of the Rifle Brigade" title="Hampshire Records Office: The Royal Green Jackets Regimental Archive: 170A12W/P/4636">
<img height="300" src="/images/serjeantsMess/serjeantsMessKey.jpg" alt="Serjeants' mess portraits assigned a number from 1 to 48" title="Serjeants' Mess Key">
</p>
<p align="center">
Portraits of the serjeants' mess of the Rifle Brigade 1st Battalion 1868. Hampshire Records Office: The Royal Green Jackets Regimental Archive: 170A12W/P/4636
</p>

The following images have been taken from the set of portraits and number based on the key.

<center>
{% for serjeant in site.data.serjeants %}
<div class="columns">
<div class="column table text">
 <h1> No: {{ serjeant.number }}. Medals - {{ serjeant.noOfMedals }} </h1>
 <h2> {{ serjeant.name }} </h2>
 <p> {{ serjeant.notes }} </p>
</div>
<div class="column table image">
 <img width="256" src="/images/serjeantsMess/SerjeantsMess_{{serjeant.number}}.jpg">
</div>
</div>
{% endfor %}
</center>
