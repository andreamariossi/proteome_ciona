# Quantitative Proteome Dynamics Across Embryogenesis in *Ciona*

[![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.isci.2024.109432-blue)](https://doi.org/10.1016/j.isci.2024.109355)
![GitHub last commit](https://img.shields.io/github/last-commit/andreamariossi/proteome_ciona)

**Code repository for:** "Quantitative proteome dynamics across embryogenesis in a model chordate"  
**Journal:** Cell iScience  
**DOI:** [10.1016/j.isci.2024.109432](https://doi.org/10.1016/j.isci.2024.109355)

**Authors:** Andrea Mariossi * Alexander Frese et al.

---

## Overview
This repository contains the complete analysis code and processed data for the quantitative proteomics study of embryonic development in the chordate *Ciona*. The paper presents the first comprehensive atlas of protein expression dynamics across early embryogenesis in a basal chordate model system.

**Key Findings:**
- Temporal proteome quantification across 8 embryonic stages
- Identification of ~7000 proteins with dynamic expression patterns
- Discovery of stage-specific protein clusters and regulatory modules
- Integration with transcriptomic data revealing post-transcriptional regulation
- Evolutionary conservation analysis between *Ciona robusta* and *Xenopus Laevis*

## Data Sources
- **Proteomics RAW files**: PRIDE Archive PXD043619
- **RNA-seq data**: GEO Series GSE237005
- **Processed protein matrices**: This repository (`data/`)

## Repository Structure
```
proteome_ciona/
├── annotation/             # Metadata and annotation
├── data/                   # Data files
│   ├── RBH/                # Reciprocal Best Hit BLAST cioan vs frog
│   └── protein/          	# Protein time series
│   └── rna_ciona/          # RNA time series
│   └── protein_ciona/      # Protein
│   └── protein_frog_1/     # Protein dataset for frog from Quantitative Proteomics for Xenopus Embryos II, Data Analysis
│   └── protein_frog_2/     # Protein dataset for frog from Transitions in the proteome and phospho-proteome during Xenopus laevis development
│   └── LDA/          		# LDA for protein QC
├── scripts/                # Analysis scripts
│   ├── preprocessing/      # Data cleaning and normalization
│   ├── analysis/         	# All figures
├── html_files/             # Rendered analysis reports (HTML) - If GitHub does not render an HTML file correctly, download it and open it locally (Chrome/Safari/Firefox).
```
