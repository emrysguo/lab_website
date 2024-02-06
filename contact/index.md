---
title: Contact
nav:
  order: 4
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Thank you for your interest! Whether you have questions about our ongoing research, collaboration opportunities, or you simply want to get in touch, we would love to hear from you. Please feel free to reach out to us using the contact information below.

{%
  include button.html
  type="email"
  text="vwani@ee.ucla.edu"
  link="vwani@ee.ucla.edu"
%}
{%
  include button.html
  type="phone"
  text="(310) 206-4975"
  link="+1-310-206-4975"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/2nfGArdWHapyF1MS6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

<!-- {% include cols.html col1=col1 col2=col2 %} -->

{% include section.html dark=true %}

<!-- {% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %} -->

<!-- {% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %} -->

<!-- {% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %} -->

<!-- {% include cols.html col1=col1 col2=col2 col3=col3 %} -->
