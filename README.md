# scRNA-seq-Data-Analysis

## Overview

This repository contains scripts for the analysis of human glioblastoma single-cell transcriptomes. The purpose of this computational workflow is to identify transcriptional programs associated with mTOR signaling, interferon response, and mesenchymal versus proneural cellular states. This workflow covers raw data quality control, data integration, CNV inference, transcriptional regulatory mechanisms, and differential expression analyses. 

## Datasets

This workflow utilizes a publicly available human glioblastoma scRNA-seq dataset from 10x Genomics v3 chemistry:

* SL040

This dataset contains data from over 130,000 cells of human glioblastoma tumor core tissue and the matching macroscopically normal cortex tissue. This dataset can be viewed and downloaded from this link: https://cellxgene.cziscience.com/datasets

## Workflow Summary

### Script1-QCNormalization.ipynb

* Generate standard Scanpy QC plots for scRNA-seq data before and after filtering
* Run Scanpy preprocessing 
* Identify highly variable genes (HVGs) and perform PCA
* Create neighborhood graph, UMAP, and clusters


###
