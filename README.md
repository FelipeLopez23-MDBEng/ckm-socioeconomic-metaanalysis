A Decade Lost to Deprivation: Socioeconomic Gradients and Advanced Cardiovascular-Kidney-Metabolic (CKM) Syndrome—A Multi-Cohort Meta-Analysis

**Affiliations:**
* School of Medicine, Universidad El Bosque, Bogotá, Colombia
* School of Medicine, Fundación Universitaria Juan N. Corpas, Bogotá, Colombia

## Overview
This repository contains the reproducible R statistical pipeline, harmonized biomarker definitions, and high-resolution figures for our two-stage individual participant data (IPD) meta-analysis evaluating socioeconomic gradients in Cardiovascular-Kidney-Metabolic (CKM) syndrome across four independent US cohorts (NHANES 2011–2012, 2013–2014, 2015–2016, and 2017–March 2020; **N = 15,046** adults aged 30–79 years).

## Key Findings
* **Three-Fold Excess Burden:** Living below the poverty threshold (PIR < 1.00) more than triples the adjusted odds of advanced CKM Stages 3–4 (**Pooled aOR 3.05**; 95% CI, 2.46–3.79; *p* = 4.96 × 10⁻²⁴) compared with high-income peers (PIR ≥ 4.00).
* **Complete Temporal Consistency:** Between-cohort heterogeneity was **I² = 0.0%** across all socioeconomic tiers over a full decade of surveillance.
* **Premature Biological Acceleration:** Adults in poverty reach the 15.3% national advanced CKM threshold at **age 54 versus age 64** among high-SES peers—a 10-year acceleration.

## Repository Contents
* `CKM_MetaAnalysis_Pipeline.R` — End-to-end R script for CDC data extraction, race-free CKD-EPI 2021 eGFR calculation, AHA PREVENT™ 10-year CVD risk equations, survey-weighted logistic models (`survey`), and REML random-effects meta-analysis (`metafor`).
* `HMS_MetaAnalysis_Poster_BLUE_FINAL.png` — Multi-cohort Forest Plot (Panel A) and pooled dose-response gradient (Panel B).
* `HMS_MetaAnalysis_Fig3_Trajectory_BLUE_FINAL.png` — Natural cubic spline age trajectories (Panel C).
* `HMS_CKM_Stages_Diagram_BLUE.png` — Visual AHA CKM Stages 0–4 hierarchy.
* `HMS_CKM_Poster_2026.pdf` — Printable poster PDF (48 × 36 in).
