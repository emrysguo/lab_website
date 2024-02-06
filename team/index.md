---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet the brilliant minds driving innovation and discovery at here. Our diverse and dedicated team of researchers brings together a wealth of expertise. Led by Principal Investigator Professor Vwani Roychowdhury and Professor Hiroki Nariai, our collaborative efforts fuel the success of projects such as classification in intercrinal EEG recording and PyHFO. Each team member contributes a unique perspective, fostering a dynamic and inclusive research environment. Explore the profiles of our researchers to learn more about their backgrounds, interests, and contributions to the scientific community. Together, we share a common passion for advancing knowledge and making a meaningful impact.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

<!-- {% include section.html background="images/background.jpg" dark=true %} -->

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. -->

{% include section.html %}

{% capture content %}

<!-- {% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %} -->

{% endcapture %}

{% include grid.html style="square" content=content %}
