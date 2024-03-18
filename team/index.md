---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# Lab Director

{% capture floatcontent %}


{% include portrait.html lookup="angeloudis-p" nointerests=true %}

{% endcapture %}

{% include float.html content=floatcontent %}


{% assign member = site.members | where: "slug", "angeloudis-p" | first %}

{% for affiliation in member.affiliations %}
<p style="margin: 0.1px; color: rgb(60,60,60)"> -  <b>{{ affiliation }}</b> </p>
{% endfor %}


Dr Panagiotis Angeloudis is Reader in Transport Systems & Logistics at the **Centre for Transport Engineering & Modelling** (CTEM) and the **Department of Civil & Environmental Engineering** at **Imperial College London**. His research focuses on the intersection of vehicle autonomy, multi-agent systems modelling, network optimisation and their applications to fleet operations, freight and maritime transport. &nbsp;&nbsp;&nbsp; _<a href="/members/angeloudis-p.html">(more)</a>_

{% include section.html %}

# Research Team


{% include list.html data="members" component="portrait" filters="role: senior" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$|senior$)" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
