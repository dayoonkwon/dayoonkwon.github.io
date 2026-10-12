---
layout: page
title: Tools for measuring biological aging
description: Open-source software that makes biological age measurable across cohorts.
importance: 3
github: https://github.com/dayoonkwon/BioAge
related_publications: true
---

Biological aging research depends on measures that different teams can compute the same way in different datasets. I build open tools that make this possible.

I developed the BioAge R package, which implements three published methods for quantifying biological age from routine blood chemistry and organ function tests: Klemera-Doubal Method biological age, phenotypic age, and homeostatic dysregulation. The package trains the algorithms in NHANES and projects them onto new datasets, so that researchers without specialized training can measure biological aging in their own cohorts {% cite kwon2021_bioage %}.

These measures support studies of how everyday exposures relate to aging. For example, in a nationally representative sample of US adults, higher intake of ultra-processed food was associated with older biological age, partly independent of overall diet quality {% cite cardoso2024_upf_phenoage %}. I also contributed to Biolearn, an open-source framework from the Biomarkers of Aging Consortium that standardizes the evaluation of 39 aging biomarkers across more than 20,000 individuals {% cite ying2025_biolearn %}.

My next step is to move from clinical chemistry to omics-based clocks, using machine learning on epigenomic, proteomic, and metabolomic data to build aging measures that are sensitive to environmental exposures.
