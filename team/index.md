---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Current members of the Danika Bannasch Genetics Laboratory.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'lab_manager'" %}
{% include list.html data="members" component="portrait" filter="name == 'Scarlett Varney'" %}


{% include section.html %}

{% include list.html data="members" component="portrait" filter="name == 'Matthew Kramer'" %}
{% include list.html data="members" component="portrait" filter="name == 'Sebastian Moretti'" %}
{% include list.html data="members" component="portrait" filter="name == 'Yeram Hong'" %}


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
