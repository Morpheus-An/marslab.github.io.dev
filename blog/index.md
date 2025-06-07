---
title: Blog
nav:
  order: 5
  tooltip: Activities and life
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}Blog

{% include figure.html 
   image="images/members/mars_lab_team.jpg" 
   link="team"
   caption="Team of MARS Lab" 
   img_style="object-fit: contain; width: 100%; height: 100%;" 
%}

We record our lab life, team building, and academic activities here.

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
