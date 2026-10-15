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
  text="andrea [dot] adden [at] bristol.ac.uk"
  link="andrea.adden@bristol.ac.uk"
%}

{%
  include button.html
  type="address"
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

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
