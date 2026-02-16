# Spatial Transcriptomics Analysis of Breast Tumor Microenvironment (GSE211729)

Bootcamp Bioinformatics Project 2 – 2026

## Background

Breast cancer progression is influenced not only by tumor cells but also by the surrounding microenvironment. 
This project analyzes spatial transcriptomics data from dataset GSE211729 to identify differentially expressed genes across tumor, stroma, and non-tumor tissues.

Understanding spatial gene expression patterns may help reveal biological mechanisms underlying tumor proliferation and microenvironment remodeling.

## Objective
- Identify differentially expressed genes (DEGs) between tumor and non-tumor tissues
- Analyze pathway enrichment patterns
- Interpret biological implications of significant genes

## Dataset Information
- Dataset: GSE211729
- Platform: Spatial transcriptomics
- Age range: 37–74 years
- Tissue categories:
  - Tumor
  - Tumor Adjacent Normal Tissue
  - Non-Tumor Bearing Breast
- Molecular Subtypes:
  - LumA
  - LumB
  - Basal
  - Normal
  - NTB
 
## Methodology
1. Data accessed via GEO database
2. Differential expression analysis performed using GEO2R
3. Significant genes selected based on:
   - Adjusted p-value < 0.05
   - |log2 Fold Change| > 1
4. Volcano plot visualization
5. Biological pathway interpretation

## Key Findings
- 302 significant genes identified
- Downregulation observed in adipogenesis-related pathways
- Upregulation observed in proliferation-associated genes
- Tumor microenvironment shows metabolic and structural remodeling

## Biological Interpretation
Tumor regions demonstrate increased proliferation signals, while adipocyte-related genes show reduced expression, suggesting microenvironmental remodeling during tumor progression.

These findings align with known mechanisms of tumor invasion and stromal interaction.

## Repository Structure
- /data → Raw data
- /results → Differential expression results
- /figures → Volcano plot and illustrations
- README.md → Project documentation

## Author
Sarah Fahima Mumtaza 
Undergraduate Student in Bioinformatics  
2026  
