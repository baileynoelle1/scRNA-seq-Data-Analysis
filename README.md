# scRNA-seq-Data-Analysis

## Overview

This repository contains scripts for the analysis of human glioblastoma single-cell transcriptomes. The purpose of this computational workflow is to identify transcriptional programs associated with mTOR signaling, interferon response, and mesenchymal versus proneural cellular states. This workflow covers raw data quality control, data integration, CNV inference, transcriptional regulatory mechanisms, and differential expression analyses. 

## Datasets

This workflow utilizes two publicly available human glioblastoma scRNA-seq datasets from 10x Genomics v3 chemistry:

* SL040
* SL057

These datasets each contain data from over 100,000 cells of human glioblastoma tumor core tissue and the matching macroscopically normal cortex tissue. These datasets can be viewed and downloaded from this link: https://cellxgene.cziscience.com/datasets

## Workflow Summary

### QC&Integration.ipynb

* Generate standard Scanpy QC plots for scRNA-seq data before and after filtering
* Run Scanpy preprocessing and integration
* Identify highly variable genes (HVGs)
* Integrate the two processed datasets using Harmony

###
