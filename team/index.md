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
{% include list.html data="members" component="portrait" filter="name == 'Matthew Kramer'" %}
{% include list.html data="members" component="portrait" filter="name == 'Sebastian Moretti'" %}
{% include list.html data="members" component="portrait" filter="name == 'Julio Perez-Rosales'" %}
{% include list.html data="members" component="portrait" filter="name == 'Yeram Hong'" %}


{% include section.html background="images/background.jpg" dark=true %}

We are not currently looking for additional team members, but please reach out if you want to collaborate on a veterinary genetics research project.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
