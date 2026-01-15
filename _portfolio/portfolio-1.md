---
title: "In-Vivo MRI Tangles Marker"
excerpt: "Autopsy-validated pipeline for an in-vivo MRI marker of tau neurofibrillary tangles.<br/><img src='/images/VisualSummary.png' alt='In-Vivo MRI Tangles Marker visual summary'>"
collection: portfolio
---

<img src="/images/VisualSummary.png" alt="In-Vivo MRI Tangles Marker visual summary" style="width:100%; max-width:1100px; height:auto; border-radius:10px;">

## What this figure shows
This visual summary illustrates my end-to-end workflow for building an **in-vivo MRI marker of tau neurofibrillary tangles**. The central idea is to **discover pathology-anchored imaging signatures in an autopsy cohort**, train and refine models on **ex vivo MRI** (where pathology is known), and then **translate those signatures to in-vivo MRI** so the marker can be used in living cohorts.

## Pipeline (left → right)
- **Multimodal discovery:** identify candidate imaging features and biomarker/pathology correlates to define hypothesis-driven signatures.
- **Ex-vivo ML model training:** train models using ex-vivo MRI features (e.g., morphometry/DTI/R2/WMH and related measures), with careful preprocessing and feature selection to predict tangles burden.
- **In-vivo → ex-vivo translation:** generate and QC in-vivo features and map them onto the ex-vivo feature space to enable consistent scoring across modalities.
- **Marker deployment:** package the pipeline so an **in-vivo MRI input** yields a **tangles score**.
- **Testing:** validate the marker in external and/or independent datasets (e.g., Rush / ADNI / NACC) and evaluate associations with **cognition**, **blood biomarkers**, and **tau-PET**.

## Why it matters
A scalable, MRI-based tangles score can help **stratify participants**, **track neurodegeneration**, and support **clinical trial enrichment**—especially when PET or invasive measures are limited.
