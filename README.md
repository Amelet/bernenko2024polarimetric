# Insect Diversity Estimation in Polarimetric Lidar

## Overview
This repository contains the data used in the study "Insect Diversity Estimation in Polarimetric Lidar" by Dolores Bernenko, Meng Li, Hampus Månefjord, Samuel Jansson, Anna Runemark, Carsten Kirkeby, and Mikkel Brydegaard. Our research focuses on the identification of insects in flight using entomological lidar, a critical tool for ecologists to count and classify insects rapidly and non-intrusively.

## Research Objective
The primary aim of this study is to assess insect biodiversity using lidar technology. We analyze 32,533 observations of wild flying insects along a 500-meter transect, exploring the benefits of lidar polarization bands and the performance of clustering algorithms in species differentiation.

## Key Findings
- **Polarization Bands:** Analysis on the effectiveness of lidar polarization bands for differentiating insect species.
- **Clustering Algorithms:** Comparative study of Hierarchical Cluster Analysis and Gaussian Mixture Model in unsupervised clustering of lidar data.
- **Species Estimation:** Estimation of species count based on physical properties such as wing beat frequency, daily activity patterns, and spatial distribution.


A preprint of the study can be found on arXiv:
[Insect Diversity Estimation in Polarimetric Lidar - arXiv](https://arxiv.org/abs/2406.01143)


## Repository Structure

This section outlines the contents of the repository.

### `/data`
This folder contains the data used in our analysis:

- **Power Spectra Observations**
  - `PCo_obs_14June_81freq.csv` - Power spectra for 32,533 co-polarized observations.
  - `PDe_obs_14June_81freq.csv` - Power spectra for 32,533 de-polarized observations.
  - `linFreq.csv` - Corresponding frequency axis for the power spectra files (81 frequencies).

- **Timestamps and Spatial Data**
  - `Time_14June_81freq.csv` - Timestamps for each of the 32,533 observations.
  - `Range_14June_81freq.csv` - Range stamps indicating the distance at which each observation was made.