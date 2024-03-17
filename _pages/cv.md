---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
======
* Assistant Professor, University of Montpellier (oct 2023 - aug 2024)
  * Teaching : 192 H in the computer science department. details <a link="../_teaching/2023-ater.md">here </a>
  * Research : 

* PhD sutdent contract, CNRS (oct 2020 - sep-2023)
  * Studying poverty prediciton with deep learning methods and remote sensing data
  * Comparing spatial and spatio-temporal models for poverty *evolution* estimation
  * Assessing the comparison in Tanzania and Syria, then in the entire Africa and Middle-East

* Study Engineer,  (Jul-Aug 2020)
  * Ameliorate the benchmark proposed during the internship
  * Summarize the results obtained in a scientific publication.
  
* Intern hosted in LIRMM for the *Fondation pour la Recherche sur la Biodiversité (FRB)* (Feb-Jun 2020)
  * Creating a benchmark for comparing poverty prediction methodologies

* Intern in French Federation of Backgammon (2019, 2 months)
  * Automatically transcribe the game, according to a video
  * The project was quite huge to realize alone, so I stopped it after my intership

Education
======
* B.S. in Mathematics, La Rochelle University, 2015-2018
* M.S. in Mathematics, La Rochelle University, 2018-2020
* Ph.D in Computer Science, University of Montpellier, 2020-2024


  
Skills
======
* Python
  * _Data_: Numpy, Scipy, Pandas, Matplotlib
  * _Image/Video_: Opencv, Scikit-Image, Ffmpeg
  * _Remote Sensing_ : Rasterio, Geemap, Folium, Ipyleaflet
  * _AI/ML_ : Scikit-Learn
  * _DL_ : Tensorflow, Pytorch
* Google Cloud Platform
  * Google Earth Engine (python) API
  * Cloud Storage
* HPC Jean-Zay
  * Multi-GPU Training of deep neural network
  * Slurm
* Latex
* Git _(a little)_
* Bash _(a little)_

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Presentation
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
