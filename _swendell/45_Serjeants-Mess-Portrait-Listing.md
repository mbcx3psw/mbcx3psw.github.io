---
layout: single
title: Henry Swendell - Portrait Listing
permalink: /swendell/Serjeants-Mess-Portrait-Listing
doctype: history
tag: HJHS
---

This page is where I'll pull together my thoughts on the various portraits and who they may be.

Working on the basis that Henry was in possession of the British and Turkish Crimean medals when the photo was taken he's in one of the pictures below. The back of the photo has a note stating that the portraits were taken between 1866 and 1870.

<div class="columns image">
{% for serjeant in site.data.serjeants %}
{% if serjeant.noOfMedals == 2 %}
 <img height="256" src="/images/serjeantsMess/SerjeantsMess_{{serjeant.number}}.jpg" alt="{{serjeant.number}}" title="Number: {{serjeant.number}}">
{% endif %}
{% endfor %}
</div>

<h1> Portrait Listing and Key </h1>


![Faded image of 48 portraits arranged around the insigna of the Rifle Brigade.](/images/serjeantsMess/170A12W_P_4636.jpg "Faded image of 48 portraits arranged around the insigna of the Rifle Brigade."){: .align-center}
*Portraits of the serjeants' mess of the Rifle Brigade 1st Battalion 1868. Hampshire Records Office: The Royal Green Jackets Regimental Archive: 170A12W/P/4636*
{: .text-center}

![Faded image of 48 portraits indexed with best guess of number of medals on each portrait.](/images/serjeantsMess/serjeantsMessKey.jpg "Faded image of 48 portraits indexed with best guess of number of medals on each portrait."){: .align-center}
*Serjeants' mess portraits indexed*
{: .text-center}

The following images have been taken from the set of portraits and number based on the key.

<center>
<table>
{% for serjeant in site.data.serjeants %}
<tr>
<td>
No: {{ serjeant.number }}. Medals - {{ serjeant.noOfMedals }} <br />
{{ serjeant.notes }} <br />
{{ serjeant.name }} <br />
</td>
<td>
<img width="512" src="/images/serjeantsMess/SerjeantsMess_{{serjeant.number}}.jpg">
</td>
</tr>
{% endfor %}
</table>
</center>
