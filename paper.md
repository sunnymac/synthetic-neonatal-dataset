---
title: "A Synthetic, Clinically Inspired Neonatal Dataset for Multi-Class Disease Prediction and Trust-Aware Machine Learning"
authors:
  - name: Sanjay Makwana
    orcid: 0009-0005-1584-6257
    affiliation: 1
  - name: Seema Mahajan
    affiliation: 1
affiliations:
  - name: Indus University, Gujarat, India
    index: 1
date: 2026
---

## Summary

Machine learning research in neonatal healthcare is often constrained by limited access to high-quality, shareable datasets due to ethical, legal, and privacy considerations. To address this challenge, we present a synthetic, clinically inspired neonatal dataset designed to support methodological research in multi-class disease prediction and trust-aware machine learning.

The dataset contains synthetic neonatal records covering maternal, birth-related, and postnatal clinical features, along with nine clinically motivated disease outcome categories. It is specifically intended to enable research on uncertainty estimation, confidence-aware decision-making, probability calibration, and explainable machine learning in healthcare contexts. The dataset is entirely synthetic and does not contain real patient data.

---

## Statement of Need

Despite growing interest in applying machine learning techniques to neonatal healthcare, publicly available datasets suitable for trust-aware and uncertainty-aware modeling remain scarce. Existing datasets often focus on single conditions, binary outcomes, or lack sufficient documentation to support reproducible research.

The presented dataset addresses this gap by providing a reusable, well-documented synthetic resource that supports multi-class disease prediction and advanced trust-aware modeling paradigms. By explicitly documenting clinically inspired feature groupings and providing clear ethical and usage guidelines, this dataset enables researchers to develop, evaluate, and benchmark reliability-aware machine learning methods without the risks associated with real patient data.

---

## Dataset Description

The dataset consists of a consolidated tabular file in CSV format, where each row represents a synthetic neonatal case. Features are derived from clinically inspired categories including maternal and antenatal information, delivery and birth characteristics, and postnatal vitals, laboratory indicators, and interventions.

The target variable represents one of nine neonatal disease categories reflecting common diagnostic groupings observed in neonatal care. To support progressive and stage-wise modeling research, an accompanying metadata file documents conceptual clinical stages corresponding to feature availability, without enforcing any modeling constraints.

The dataset is designed to reflect realistic class imbalance patterns commonly observed in neonatal intensive care settings, while maintaining a synthetic and privacy-preserving structure.

---

## Availability

The dataset is publicly available on Zenodo under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.

**DOI:** https://doi.org/10.5281/zenodo.18329706
