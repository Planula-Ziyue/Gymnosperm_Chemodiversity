## Overview
This repository provides supplementary materials for the research paper titled "Distinct constraints but shared dynamics shaped macroevolution of global and core chemodiversity". These files include R code for reproducing the analyses, datasets used in the study, visualization outputs, and supplementary tables referenced in the paper (e.g., Tables S1–S6).
The materials are organized to facilitate replication of the results. The Rmd files contain all necessary code for the key analyses, the CSV and XLSX files serve as input data or intermediate outputs. They should be executed for full replication, with data files placed in the working directory.

## File Descriptions
### `R` codes (.Rmd)
- `01_Global_chemodiversity.Rmd`: Code for analyzing global chemodiversity.
- `02_Core_chemodiversity.Rmd`: Code focused on core chemodiversity, covering constraints and dynamics specific to core chemical diversity.
- `03_Matrix_perturbation.Rmd`: Code for matrix perturbation analysis.

### Data Files (.csv)
These CSV files are essential inputs or procedural intermediates for the reproduction workflow.

- `AllGymnnoData.csv`, `AllGymnnoData_with_taxonomy_info.csv`: Dataset of gymnosperm global chemodiversity data used across analyses.
- `forASR.csv`,`forTip.csv`: Dataset prepared for Ancestral State Reconstruction analyses.
- `gymno_phy_pca_scores.csv`: Phylogenetic Principal Component Analysis (PCA) scores derived from gymnosperm VOC data matrix.
- `MajorGymnoData.csv`: Dataset of gymnosperm core chemodiversity data used across analyses.

### Supplementary Tables (S1–S6)
These files correspond directly to the supplementary tables mentioned in the paper.

- `Supplementary_table_1.xlsx`: Table S1 
- `Supplementary_table_2.xlsx`: Table S2 
- `Supplementary_table_3.csv`: Table S3
- `Supplementary_table_4.xlsx`: Table S4
- `Supplementary_table_5.csv`: Table S5 
- `Supplementary_table_6.xlsx`: Table S6
