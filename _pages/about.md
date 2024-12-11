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
I am a undergraduate researcher at University of Connecticut.
My research interests lie primarly in city- and building-scale disaster prediction. I an anticipated to received my B.A. from the Statistics Department and Economics Department. [University of Connecticut](https://uconn.edu/).

## Research Experience
**05/2024 - Present | Research Assistant | Department of Statistics, University of Connecticut**
* Conducted preliminary research for city-scale and building-scale disaster prediction by estimating building heights, reprocessing the UT-GLOBUS dataset, developing interactive maps, and performing exploratory spatial data analysis.
* Preprocessed satellite data with QGIS and SNAP, combined with other datasets including OpenStreetMap building footprints, and applied Random Forest Regression to predict urban building heights for disaster modeling.
* Reprocessed data of 413 major U.S. cities (gpkg files) from UT-GLOBUS datasets using HPC, calculating coordinates for each building and exporting attributes of each city into individual CSV files.
* Developed an interactive map using data from New Haven to visualize building footprints and associated attributes. Integrated exploratory spatial data analysis across 4 cities to examine spatial autocorrelation and enhance visualization insights.
* Created a detailed tutorial to ensure reproducibility of data preprocessing, integration, and analysis workflows.

## Internship Experience
**01/2024 - 05/2024 | Intern | Qian Shi Du**
* Performed time series analysis to compare current and historical trends and developed a GPT-based model to forecast customer demand patterns, with SHAP values used to interpret feature importance.
* Employed K-means to segment customer preferences, guiding targeted product development and marketing.
* Integrated insights from customer segmentation, purchasing behavior, and product tracking to forecast sales trends, supporting the company's strategic decision-making in international trade.

**05/2024 - 08/2024 | Intern | GBCS-SkyIT**
* Developed backend services for the Voop application using Express.js and Django REST, contributing to scalable architecture and API integration.
* Collaborated with teammates in migrating database from Firebase to MySQL, optimizing database schema, and ensuring data accuracy during the transition.
* Built and tested APIs for Voop, utilizing Postman to debug and validate functionality.

## Project
**Bytedance - Data Optimization and Algorithm Enhancement | Remote Collaboration**
* Preprocessed large-scale text data, using techniques such as tokenization and stemming to improve data quality and enhance search engine performance.
* Applied a SAITS model for data imputation and fine-tuned a LLaMA2 model by LoRA to predict product prices based on descriptions, addressing missing data challenges.
* Optimized product price prediction algorithms by refining code efficiency and improving data pipelines, resulting in increased accuracy and operational performance.

**Exploratory Data Analysis in NYC Open Data—Rodent Inspection | Statstics Course (Introduction to Data Science)**
* Cleaned and analyzed NYC rodent inspection data using methods like binomial regression models.
* Designed an interactive map with GeoPandas to display rodent sighting locations with all related information and displayed the result to the NYC Open Data team to support rodent inspection.

**Prediction of NBA Players’ Salary based on On-Court Contributions | Statstics Course (Introduction to Statistical Learning)**
* Cleaned and conducted exploratory data analysis on on-court statistics to examine their correlation with player salaries.
* Utilized 4 machine learning models and applied methods such as hyperparameter tuning, Bayesian optimization, and model ensembling to improve prediction accuracy.

## Miscellaneous
Activities I find enjoyable: baskerball, reading, writing, and more.

{% assign filenames = "molly1.png,molly2.png,molly3.png,molly4.png,molly5.png,molly6.png" | split: "," %}
<div class ="image-gallery">
{% for name in filenames %}
    <div class="box">
    <a href="{{ site.url }}{{ site.baseurl }}/images/{{ name }}">
      <img src="{{ site.url }}{{ site.baseurl }}/images/{{ name }}" alt="{{ name }}"  class="img-gallery" />
     </a>
    </div>
 {% endfor %}
</div>
