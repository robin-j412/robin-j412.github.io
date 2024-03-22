---
title: "First steps with Geemap."
collection: talks
type: "Tutorial"
permalink: /talks/2022-10-12-gdr-pic-strong
venue: "<i>GdR PIC - STRONG, UMR Espace-dev, IRD</i>"
date: 2022-10-20
location: "Virtual event."

---
A ready to use short demonstration of several possibilities with Geemap. The objective is to show that, with minimum effort, it's possible to create a model that estimates the population count for a given lat/lon and create an interactive map to visualize the results.

[Link to GitHub](https://github.com/robin-j412/geemap-demo)

---

<iframe src="/maps/pred_map.html" width="820" height="520"></iframe> -->

Train data is on the left and test data on the right. A Decision Tree Regressor is trained at the pixel level, to estimate the population count, given by the [Worlpop](https://developers.google.com/earth-engine/datasets/catalog/WorldPop_GP_100m_pop) dataset. 
On the test side, we observe some a radically different spatial pattern: the model produce a higher resolution map that seem globally consistent with the background high resolution optical imagery. 
However there are also a high proportion of error predictions (with high population count in marsh for examples ...)
