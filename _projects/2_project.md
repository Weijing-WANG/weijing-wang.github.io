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

<div class="row mt-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/P2_GWR_Local_Coefficients.png" title="GWR local coefficients" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/P2_shap_dependence_plots.png" title="SHAP dependence plots" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Spatial distribution of local coefficients from the GWR model showing how design factors vary across locations. Right: SHAP partial dependence plots reveal the relationship between site planning features and emotional responses.
</div>

---

## Our Approach

<div class="row justify-content-center mt-3 mb-3">
    <div class="col-md-8">
        <p style="font-size: 1.1rem; line-height: 1.8; text-align: center;">
            <strong>Input:</strong> Site planning layouts<br>
            <strong>Model:</strong> Deep learning (PyTorch)<br>
            <strong>Output:</strong> Emotional response predictions
        </p>
    </div>
</div>

---

## What We Found

<div class="row justify-content-center mt-4 mb-4">
    <div class="col-md-10">
        <div style="background-color: #f8f9fa; padding: 2rem; border-radius: 8px; border-left: 4px solid #dc3545;">
            <p style="font-size: 1.05rem; line-height: 1.7; margin-bottom: 0; color: #495057;">
                Open and visually connected spatial forms—such as <strong>line-like slabs</strong> and <strong>symmetrical layouts</strong>—tend to evoke more positive emotional responses. In contrast, enclosed, mono-functional, or overly uniform configurations, like transport buildings or enclosed blocks, may limit emotional stimulation and reduce perceived vibrancy.
            </p>
        </div>
    </div>
</div>

**Design elements that predict positive emotions:**

<div class="row mt-3">
    <div class="col-md-6">
        <ul style="font-size: 1rem; line-height: 1.8;">
            <li> <strong>Open spatial forms</strong> - Line-like slabs significantly boost positive emotions</li>
            <li> <strong>Symmetrical layouts</strong> - Approximate symmetry and axis-guided designs enhance well-being</li>
            <li> <strong>Mixed functionality</strong> - Public and residential buildings promote vibrancy over transport facilities</li>
        </ul>
    </div>
    <div class="col-md-6">
        <ul style="font-size: 1rem; line-height: 1.8;">
            <li> <strong>Landscape diversity</strong> - Higher Simpson Index (moderate levels) correlates with positive emotions</li>
            <li> <strong>Transit accessibility</strong> - High accessibility (>2.0) strongly increases emotional responses</li>
            <li> <strong>Low connectivity paradox</strong> - Extremely high connectivity may reduce emotional stimulation</li>
        </ul>
    </div>
</div>

---

<div class="row justify-content-center mt-5">
    <div class="col-md-10">
        <p style="font-size: 0.95rem; color: #6c757d; margin-bottom: 0.5rem;">
            <strong>Publication:</strong> Cao, Q., <strong>Wang, W.</strong> (corresp.), & Stouffs, R. (2025). Emotional Responses to Site Planning Layouts: A Data-Driven Analysis Using Deep Learning. <em>CAAD Futures 2025</em>, Springer.
        </p>
        <p style="font-size: 0.95rem; color: #6c757d; margin-bottom: 0.5rem;">
            <strong>Institution:</strong> National University of Singapore, 2024-2025
        </p>
        <p style="font-size: 0.95rem; color: #6c757d;">
            <strong>Tech Stack:</strong> PyTorch • Computer Vision • Deep Learning • SHAP • GWR
        </p>
    </div>
</div>
