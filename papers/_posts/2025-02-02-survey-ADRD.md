---
layout: paper
title: "Machine-learning models for Alzheimer’s disease diagnosis using neuroimaging data: survey, reproducibility, and generalizability evaluation"
nickname: Survey-ADRD-2025
authors: "Maryam Akhavan Aghdam; Serdar Bozdag; Saeed, Fahad; "
year: "2025"
journal: "Springer Brain Informatics"
volume: 
issue: 12, article number: 8
pages: 1-27
is_published: True
image: /assets/images/papers/springer.png
projects: [ML-ADRD]
tags: [journal]

# Text
fulltext: https://braininformatics.springeropen.com/articles/10.1186/s40708-025-00252-3
pdf: 
pdflink: https://braininformatics.springeropen.com/counter/pdf/10.1186/s40708-025-00252-3.pdf
pmcid:
preprint: 
supplement:

# Links
doi: 10.1186/s40708-025-00252-3
pmid: 

# Data and code
github: 
neurovault:
openneuro: []
figshare:
figshare_names:
osf:
---
{% include JB/setup %}

# Abstract

Clinical diagnosis of Alzheimer’s disease (AD) is usually made after symptoms such as short-term memory loss are exhibited, which minimizes the intervention and treatment options. The existing screening techniques cannot distinguish between stable MCI (sMCI) cases (i.e., patients who do not convert to AD for at least three years) and progressive MCI (pMCI) cases (i.e., patients who convert to AD in three years or sooner). Delayed diagnosis of AD also disproportionately affects underrepresented and socioeconomically disadvantaged populations. The significant positive impact of an early diagnosis solution for AD across diverse ethno-racial and demographic groups is well-known and recognized. While advancements in high-throughput technologies have enabled the generation of vast amounts of multimodal clinical, and neuroimaging datasets related to AD, most methods utilizing these data sets for diagnostic purposes have not found their way in clinical settings. To better understand the landscape, we surveyed the major preprocessing, data management, traditional machine-learning (ML), and deep learning (DL) techniques used for diagnosing AD using neuroimaging data such as structural magnetic resonance imaging (sMRI), functional magnetic resonance imaging (fMRI), and positron emission tomography (PET). Once we had a good understanding of the methods available, we conducted a study to assess the reproducibility and generalizability of open-source ML models. Our evaluation shows that existing models show reduced generalizability when different cohorts of the data modality are used while controlling other computational factors. The paper concludes with a discussion of major challenges that plague ML models for AD diagnosis and biomarker discovery.