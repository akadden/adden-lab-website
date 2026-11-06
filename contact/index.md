---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Get in touch!

{%
  include button.html
  type="email"
  text="Send us an email"
  link="andrea.adden@bristol.ac.uk"
%}

{%
  include button.html
  type="address"
  text="Visit us at the Life Sciences Building"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/28ZneLQsv3qwvHQEA"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/LSB.jpeg"
  caption="Inside the Life Sciences Building"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/miranda_tsetse.jpeg"
  caption="Credit: Miranda Gonzales"
%}

{% endcapture %}
