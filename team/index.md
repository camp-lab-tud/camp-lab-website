---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a multidisciplinary team at TU Delft led by Prof. Baris Caglar. Our research combines experimental techniques and numerical approaches, including machine learning, to study the properties of composite materials and their manufacturing. We believe great science happens in open, diverse, and collaborative yet excellence-minded environments, and our team reflects those values.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

{% include section.html background="images/background.jpg" dark=true %}
{% include button.html icon="fa-solid fa-handshake-angle" text="Join us!" link="join" style="button" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-graduation-cap" %}Alumni

{% include list.html data="members" component="portrait" filter="role != 'alumni'" style="small"  %}

# {% include icon.html icon="fa-solid fa-building-columns" %}Funding