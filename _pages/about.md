---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



## Biography
I am a undergraduate researcher at University of Connecticut.
My research interests lie primarly in city- and building-scale disaster prediction. I an anticipated to received my B.A. from the Statistics Department and Economics Department. [University of Connecticut](https://uconn.edu/).

## Experience
**01/2024 - 05/2024 | Intern | Qian Shi Du

**05/2024 - 08/2024 | Intern | GBCS-SkyIT
* Developed backend services for the Voop application using Express.js and Django REST, contributing to scalable architecture and API integration.

## Project
**Bytedance - Data Optimization and Algorithm Enhancement | Remote Collaboration

**Exploratory Data Analysis in NYC Open Data—Rodent Inspection | Statstics Course (Introduction to Data Science)

**Prediction of NBA Players’ Salary based on On-Court Contributions | Statstics Course (Introduction to Statistical Learning)

## Miscellaneous
Activities I find enjoyable: baskerball, reading, writing, and more.

{% assign filenames = "molly1.png,molly2.png,molly3.png,molly4.png,molly5.png,molly6.png" | split: "," %}
<div class ="image-gallery">
{% for name in filenames %}
    <div class="box">
    <a href="{{ site.url }}{{ site.baseurl }}/assets/img/cat/full/{{ name }}">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/molly/thumbs/{{ name }}" alt="{{ name }}"  class="img-gallery" />
     </a>
    </div>
 {% endfor %}
</div>
