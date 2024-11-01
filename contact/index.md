---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the [School of Mechanical and Aerospace Engineering](https://www.ntu.edu.sg/mae/), at [Nanyang Technological University](https://www.ntu.edu.sg).

We are located at [N3-01a-01, Block N3, 50 Nanyang Ave, 639798](https://www.google.com/maps/place/Block+N3/@1.3471362,103.5378257,12z/data=!3m1!5s0x31da0f754e8195cb:0x556fd948c6a7f965!4m10!1m2!2m1!1sN3!3m6!1s0x31da0f750415f4a3:0x762030a8d62432b9!8m2!3d1.3471362!4d103.6820213!15sCgJOM5IBCnVuaXZlcnNpdHngAQA!16s%2Fg%2F1ptwyh4g3?entry=ttu&g_ep=EgoyMDI0MTAyNy4wIKXMDSoASAFQAw%3D%3D).

{%
  include button.html
  type="email"
  text="jianfei.yang@ntu.edu.sg"
  link="jianfei.yang@ntu.edu.sg"
%}
{%
  include button.html
  type="phone"
  text="(65) 6790-4936"
  link="+65-6790-4936"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Block+N3/@1.3474987,103.6793986,17z/data=!3m1!5s0x31da0f754e8195cb:0x556fd948c6a7f965!4m10!1m2!2m1!1sNTU+Block+N3!3m6!1s0x31da0f750415f4a3:0x762030a8d62432b9!8m2!3d1.3471362!4d103.6820213!15sCgxOVFUgQmxvY2sgTjOSAQp1bml2ZXJzaXR54AEA!16s%2Fg%2F1ptwyh4g3?entry=ttu&g_ep=EgoyMDI0MTAyNy4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/lab/arc.jpg"
  caption="NTU Learning Center"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/lab/yunnan_garden.jpg"
  caption="NTU Yunnan Garden"
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
