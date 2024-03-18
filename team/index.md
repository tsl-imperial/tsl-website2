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


{% assign member = site.members where_exp: "member" | "member.slug == angeloudis.p" | first %}

{% for affiliation in member.affiliations %}
<p style="margin: 0.1px; color: rgb(60,60,60)"> <b>{{ - Reader in Transport Systems & Logistics  }}</b> </p>

  

<p style="margin: 0.1px; color: rgb(60,60,60)"> <b>{{ affiliation }}</b> </p>
{% endfor %}


Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

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
