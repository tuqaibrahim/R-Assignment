# Tuqa's R Assignment

This repository contains my submission for the R assignment. It is mainly about data inspection, processing, and visualization of SNP data from maize and teosinte.

## Repository organization

- `README.md`  
  Provides and overview of the contents of this repository.

- `R_Assignment.Rmd`  
  An R Markdown file containing the code and explanation of the analysis workflow.
  
- `R_Assignment.html`  
  The rendered output of the R Markdown document.

- `data/`  
  Contains the two original input data files I used in the analysis:
  - `fang_et_al_genotypes.txt`
  - `snp_position.txt`

- `output/processed_files/`  
  Contains the 40 chromosome output files generated in Part I (Data Processing):
  - 20 files for maize
  - 20 files for teosinte

- `output/visuals/`  
  Contains plots generated in Part II. (Data Visualization).

## Reproducibility

This analysis can be reproduced by opening `R_Assignment_Tuqa.Rmd` in RStudio and running all code chunks in order, or by knitting the file to HTMLL. Running the analysis code will regenerate the files in `output/reviewer_processed_files/` and `output/reviewer_visuals/`.
These regenerated files can be compared with the versions already included in the repository after downloading or cloning it from GitHub, found in `output/processed_files/` and `output/visuals/`.
