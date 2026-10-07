---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" filter="group != 'alum'" %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

{% include section.html %}

{% include list.html data="members" component="portrait" filter="group == 'alum'" %}

{% capture content %}

{% include section.html background="images/background.jpg" dark=true %}

{% endcapture %}

{% include grid.html style="square" content=content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
