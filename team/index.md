---
title: Team
nav:
  order: 3
  tooltip: Meet our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" filter="group != 'alum'" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

{% include section.html %}

{% include list.html data="members" component="portrait" filter="group == 'alum'" %}
