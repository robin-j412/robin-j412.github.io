---
title: "Assessment of CNN-Based Methods for Poverty Estimation from Satellite Images"
collection: publications
permalink: /publications/jarry-2021-assessment
excerpt: "We set up a comparison ef existing methods for poverty estimation, and compare them in Malawi."
date: 2020-02-21
venue: "ICPR International Workshops and Challenges. ICPR 2021. Lecture Notes in Computer Science vol 12667"
paperurl: "<a href='https://hal.science/hal-03066937v1'> Link.</a>"
citation: "Robin Jarry, Marc Chaumont, Laure Berti-Équille, Gérard Subsol. Assessment of CNN-based methods for poverty estimation from satellite images. In <i>Pattern Recognition. ICPR International Workshops and Challenges: Virtual Event, January 10-15, 2021, Proceedings, Part VII</i> (p. 550-565). Springer International Publishing."
---

### Abstract

One of the major issues in predicting poverty with satellite images is the lack of fine-grained and reliable poverty indicators. To address this problem, various methodologies were proposed recently. Most recent approaches use a proxy (e.g., nighttime light), as an additional information, to mitigate the problem of sparse data. They consist in building and training a CNN with a large set of images, which is then used as a feature extractor. Ultimately, pairs of extracted feature vectors and poverty labels are used to learn a regression model to predict the poverty indicators.

First, we propose a rigorous comparative study of such approaches based on a unified framework and a common set of images. We observed that the geographic displacement on the spatial coordinates of poverty observations degrades the prediction performances of all the methods. Therefore, we present a new methodology combining grid-cell selection and ensembling that improves the poverty prediction to handle coordinate displacement.

