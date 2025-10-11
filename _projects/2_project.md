---
layout: page
title: Emotional Cities
description: Can AI predict how urban spaces make you feel?
img: assets/img/p2_cover.jpg
importance: 2
category: work
giscus_comments: false
---

## What makes a place feel good?

We trained deep learning models to predict emotional responses to different site planning layouts. The goal: help designers create cities that enhance human well-being.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/P2_GWR_Local_Coefficients.png" title="Spatial distribution of local coefficients for key continuous variables from the GWR model" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/P2_shap_dependence_plots.png" title="Partial dependence plots: (a) Simpson Index; (b) Connectivity Index; (c) Public Transit
Accessibility; (d) Building form types; (e) Building functional types; (f) Layout patterns." class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Same site, different emotions. Our AI learns which design choices matter.
</div>

---

## Our Approach

**Input:** Site planning layouts  
**Model:** Deep learning (PyTorch)  
**Output:** Emotional response predictions  

---

## What We Found

<div class="caption">
Open and visually connected spatial forms — such as line-like slabs and symmetrical layouts — tend to evoke more positive emotional responses. In contrast, enclosed, mono-functional, or overly uniform configurations, like transport buildings or enclosed blocks, may limit emotional stimulation and reduce perceived vibrancy.
</div>

---

**Publication:** Cao, Q., **Wang, W.** (corresp.), & Stouffs, R. (2025). CAAD Futures, Springer.

**Where:** National University of Singapore, 2024-2025

**Tech:** PyTorch • Computer Vision • Deep Learning
