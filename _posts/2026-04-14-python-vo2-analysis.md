---
layout: post
title: "Python & Data Analysis — VO2max & Physiological Thresholds"
date: 2026-04-14
order: 1
categories: [Python, Kinesiology]
tags: [python, matplotlib, numpy, pandas, VO2max, data analysis]
---

## Overview

As part of KNES 381 (Computer Applications in Kinesiology) at the University of Calgary, I developed a Python script that analyzes a VO2 dataset to identify key physiological thresholds. The dataset was sourced from Kaggle and processed using NumPy, Pandas, and Matplotlib.

---

## What is VO2max?

VO2max represents the maximum rate at which the body can consume oxygen during intense exercise. It is one of the strongest predictors of cardiovascular fitness and endurance performance. A higher VO2max means the body can deliver and use more oxygen — translating directly to better aerobic capacity.

Alongside VO2max, two critical thresholds help paint a fuller picture of an athlete's aerobic profile:

- **GET (Gas Exchange Threshold)** — the point where VCO₂ begins rising non-linearly, signaling the transition from aerobic to mixed energy metabolism. Identified via the V-slope method.
- **RCP (Respiratory Compensation Point)** — where FECO₂ drops after its plateau indicating the onset of hyperventilation and the upper limit of sustainable high-intensity effort.

Understanding where these thresholds fall relative to VO2max allows coaches and
clinicians to design precise training zones and assess an athlete's readiness for
competition.

---

## The Analysis

The script processes breath-by-breath gas exchange data and programmatically plots VO2 over time, marking GET and RCP as vertical reference lines. A second figure plots FECO₂ and VCO₂ against VO2 to visualize the gas exchange dynamics that define each threshold.

All charts update automatically when the underlying data or threshold values are changed.

**Tools used:** Python, NumPy, Pandas, Matplotlib, Kaggle Notebooks

---

## Notebook

<iframe src="https://www.kaggle.com/embed/joaopelinca/vo2-script-ipynb?kernelSessionId=311669436" height="800" style="margin: 0 auto; width: 100%; max-width: 950px;" frameborder="0" scrolling="auto" title="vo2_script.ipynb"></iframe>