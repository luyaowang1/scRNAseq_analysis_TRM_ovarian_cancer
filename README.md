# scRNAseq_analysis_TRM_ovarian_cancer
# scRNA-seq QC and analysis

This repository contains the R scripts used for single-cell RNA-seq data processing and analysis.

## Overview

The analysis includes:
- Quality control filtering
- Ambient RNA correction using decontX
- Doublet detection using DoubletFinder
- Clustering and UMAP visualization

All analyses were performed using standard workflows implemented in Seurat and related packages.

## Files

- `analysis_pipeline.R`  
  Main script for data processing and analysis.

- `sessionInfo.txt`  
  R session information for reference.

## Notes

The scripts reflect the workflow used in this study and are provided for transparency.  
Depending on the local environment and data structure, minor adjustments may be required to run the code.

Some sample-specific handling steps are retained in the script.
