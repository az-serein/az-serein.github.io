---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style type="text/css">
   /*! div style */
  .image-gallery {
    width: 100%;
    display: grid;
    grid-template-columns: repeat(auto-fill,minmax(200px, 1fr));
    justify-content: center;
    padding: 4px;
  }

  .box {
      flex-basis: 25%;
      width: 100%;
      padding: 10px;
      margin: 2px;
  }

  .img-gallery {
	width: 100%;
  height: 200px;
	object-fit: cover;
  transform: scale(1);
  transition: all 0.3s ease-in-out;
  }
  .img-gallery:hover {
    transform: scale(1.05);
  }
</style>

## Biography
I am a Undergraduate Researcher at University of Connecticut.
My research interests lie primarly in city- and building-scale disaster prediction. I an anticipated to received my B.A. from the Statistics Department and Economics Department. [University of Connecticut](https://uconn.edu/).

## Experience
**01/2024 - 05/2024 | Intern | Qian Shi Du

** 05/2024 - 08/2024 | Intern | GBCS-SkyIT
* Developed backend services for the Voop application using Express.js and Django REST, contributing to scalable architecture and API integration.

## Project

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
