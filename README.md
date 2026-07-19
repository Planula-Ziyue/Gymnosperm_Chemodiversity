## Overview
This repository provides supplementary materials for the research paper titled "Distinct constraints but shared dynamics shaped macroevolution of global and core chemodiversity". These files include R code for reproducing the analyses, datasets used in the study, visualization outputs, and supplementary tables referenced in the paper (e.g., Supplementary Data Files 1–6).
The materials are organized to facilitate replication of the results. The Rmd files contain all necessary code for the key analyses, the CSV and XLSX files serve as input data or intermediate outputs. They should be executed for full replication, with data files placed in the working directory.

## File Descriptions
### `R` codes (.Rmd)
- `01_Global_chemodiversity.Rmd`: Code for analyzing global chemodiversity.
- `02_Core_chemodiversity.Rmd`: Code focused on core chemodiversity, covering constraints and dynamics specific to core chemical diversity.
- `03_Matrix_perturbation.Rmd`: Code for matrix perturbation analysis.

### Intermediate Files for running codes
These CSV files are essential inputs or procedural intermediates for the reproduction workflow.

- `AllGymnnoData.csv`, `AllGymnnoData_with_taxonomy_info.csv`: Dataset of gymnosperm global chemodiversity data used across analyses.
- `forASR.csv`,`forTip.csv`: Dataset prepared for Ancestral State Reconstruction analyses.
- `gymno_phy_pca_scores.csv`: Phylogenetic Principal Component Analysis (PCA) scores derived from gymnosperm VOC data matrix.
- `MajorGymnoData.csv`: Dataset of gymnosperm core chemodiversity data used across analyses.

### Supplementary Data File (1-6)
These files correspond directl1-6y to the supplementary tables mentioned in the paper.

- `Supplementary_Data_File_1.xlsx`: Supplementary Data File 1 
- `Supplementary_Data_File_2.xlsx`: Supplementary Data File S2 
- `Supplementary_Data_File_3.csv`: Supplementary Data File S3
- `Supplementary_Data_File_4.xlsx`: Supplementary Data File S4
- `Supplementary_Data_File_5.csv`: Supplementary Data File S5 
- `Supplementary_Data_File_6.xlsx`: Supplementary Data File S6

### Autocorrelation Plots
- `Autocorrelation_Plots.pdf`: MCMC diagnosis from `mcmcglmm` results
