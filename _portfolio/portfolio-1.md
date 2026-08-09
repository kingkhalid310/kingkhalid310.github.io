---
title: "In Vivo MRI Tangles Marker"
excerpt: "Autopsy-confirmed pipeline for an in vivo MRI marker of neurofibrillary tangles.<br/><img src='/images/VisualSummary.png' alt='In vivo MRI Tangles Marker visual summary'>"
collection: portfolio
order: 2
---

<img src="/images/VisualSummary.png" alt="In vivo MRI Tangles Marker visual summary" style="width:100%; max-width:1100px; height:auto; border-radius:10px;">

## What this figure shows
This visual summary illustrates my end-to-end workflow for building an **in vivo MRI marker of neurofibrillary tangles**. The central idea is to **discover pathology-anchored imaging signatures in an autopsy cohort**, train and refine models on **ex vivo MRI** (where pathology is known), and then **translate those signatures to in vivo MRI** so the marker can be used in living cohorts.

## Pipeline (left → right)
- **Multimodal discovery:** identify candidate imaging features and biomarker/pathology correlates to define hypothesis-driven signatures. [[Volume and Shape patterns](https://khalid-saifullah.com/portfolio/portfolio-3/)] [[AD and LATE patterns](https://khalid-saifullah.com/portfolio/portfolio-2/)]
- **Ex vivo ML model training:** train models using ex vivo MRI features (e.g., morphometry/DTI/R2/WMH and related measures), with careful preprocessing and feature selection to predict tangles burden. [[See this](https://khalid-saifullah.com/talks/2022-07-31-talk-2)]
- **In vivo → ex vivo translation:** generate and QC in vivo features and map them onto the ex vivo feature space to enable consistent scoring across modalities. [[For Reference](https://pmc.ncbi.nlm.nih.gov/articles/PMC3664651/)]
- **Marker deployment:** package the pipeline so an **in vivo MRI input** yields a **tangles score**.
- **Testing:** validate the marker in external and/or independent datasets (e.g., Rush / ADNI / NACC) and evaluate associations with **cognition**, **blood biomarkers**, and **tau-PET**.

## Why it matters
A scalable, MRI-based tangles score can help **stratify participants**, **track neurodegeneration**, and support **clinical trial enrichment**—especially when PET or invasive measures are limited.


## Resources

**ISMRM 2022** · [Abstract](https://archive.ismrm.org/2022/0718.html)  
**AAIC 2022** · [Abstract](https://alz-journals.onlinelibrary.wiley.com/doi/full/10.1002/alz.066142)

For related work from our lab, see **ARTS** **[[Paper]](https://alz-journals.onlinelibrary.wiley.com/doi/10.1002/alz.70430)** **[[Software]](https://www.nitrc.org/projects/arts)** (in vivo MRI marker for arteriolosclerosis) and **MARBLE** **[[Paper]](https://archive.ismrm.org/2025/0872.html)** (in vivo MRI marker for LATE).
