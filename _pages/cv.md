---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Mathematics, La Rochelle University, 2015-2018
* M.S. in Mathematics, La Rochelle University, 2018-2020
* Ph.D in Computer Science, University of Montpellier, 2020-2023 (expected)

Work experience
======
* Summer job at the french _Embarcadère de l'Abbaye_. (2014-2018)
  * Show tourists around the Poitevin Marsh, by boat

* Intern in French Federation of Backgammon (2019, 2 months)
  * Automatically transcribe the game, according to a video
  * The project was quite huge to realize alone, so I stopped it after my intership

* Intern in LIRMM (2020, 4 month)
  * University of Montpellier
  * Creating a benchmark for comparing poverty prediction methodologies

* Study Engineer (2020, 2 month)
  * Ameliorate the benchmark proposed during the internship
  * Summarize the results obtained in a scientific publication.
  
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
* HPE Jean-Zay
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
