# Custom signature analysis for scRNA-seq data

This repository contains the custom analysis code used for signature correlation analysis in the study.

The workflow includes:
- ssGSEA scoring using GSVA
- correlation analysis between published and study-derived gene signatures
- analysis of shared CD8 T cell populations across FT and tumor samples

## Files

- `custom_signature_analysis.Rmd`  
  Main analysis workflow.

- `sessionInfo.txt`  
  R session information.

## Notes

The scripts are provided for transparency and reference purposes.  
Minor adjustments to file paths or computational environments may be required to run the analysis.

The analysis was performed using standard publicly available R packages, including Seurat and GSVA.
