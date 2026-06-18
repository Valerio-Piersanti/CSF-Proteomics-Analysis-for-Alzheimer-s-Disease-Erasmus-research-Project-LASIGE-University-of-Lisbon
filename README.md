# CSF Proteomics Analysis for Alzheimer's Disease

## Overview

This repository contains the code, figures, and presentations developed during my Erasmus research project at LASIGE, University of Lisbon.

The project investigates molecular heterogeneity in Alzheimer's Disease using cerebrospinal fluid (CSF) proteomics data. Unsupervised learning approaches were applied to identify patient subgroups and characterize their biological and clinical differences.

## Key Findings

* Two robust molecular clusters were identified using Non-negative Matrix Factorization (NMF).
* Patients belonging to the grey zone did not form a distinct molecular subtype but instead showed overlapping characteristics of the two main clusters.
* Cohort effects were detected within the dataset; however, the biological pathways identified through enrichment analyses remained consistent, suggesting that the main biological conclusions were not driven by cohort-specific biases.
* Pathway enrichment analyses provided biological characterization of the identified patient subgroups and highlighted distinct molecular mechanisms associated with each cluster.

## Research Objectives

The main objectives of this project were:

* Perform preprocessing and quality control of CSF proteomics data.
* Identify informative protein features.
* Explore patient stratification using clustering approaches.
* Investigate grey-zone patient heterogeneity.
* Assess potential cohort effects.
* Characterize biological differences through pathway enrichment analyses.

## Repository Structure

### codes/

Contains all analysis scripts organized by project stage:

* `preprocessing` – data cleaning, filtering, normalization, and quality control.
* `feature_selection` – identification of informative proteins.
* `nmf_and_enrichment` – NMF clustering and Reactome pathway enrichment analyses.
* `grey_zone_and_cohort_analysis` – investigation of grey-zone patients and cohort-related effects.
* `exploratory_models` – evaluation of alternative clustering approaches.

### images/

Figures generated throughout the project, organized according to the corresponding analysis stage.

### presentations/

Project presentations documenting project progress and final results.

## Analytical Workflow

1. Data preprocessing and quality control.
2. Feature selection.
3. Unsupervised clustering.
4. NMF-based patient stratification.
5. Grey-zone patient investigation.
6. Cohort effect assessment.
7. Pathway enrichment analysis.
8. Biological interpretation of identified patient groups.

## Technologies

* Python
* Jupyter Notebooks
* pandas
* NumPy
* scikit-learn
* matplotlib
* seaborn
* gseapy
* Reactome

## Author

Valerio Piersanti

Erasmus Research Project

LASIGE – University of Lisbon
