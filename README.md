# Tuqa's R Assignment

This repository contains my submission for the R assignment. It is manily about data inspection, processing, and visualization of SNP data from maize and teosinte.

## Repository organization

- `README.md`  
  Provides and Overview of the contents of the repository.

- `R_Assignment.Rmd`  
  An R Markdown file containing the code and explanation of the analysis workflow.
  
- `R_Assignment.html`  
  The rendered output of the R Markdown document.

- `data/`  
  This folder contains the original two input data files I used in the analysis:
  - `fang_et_al_genotypes.txt`
  - `snp_position.txt`

- `output/processed_files/`  
  This folder contains the 40 chromosome output files generated in Part I (Data Processing):
  - 20 files for maize
  - 20 files for teosinte

- `output/visuals/`  
  Contains plots generated in Part II.

## Reproducibility

This analysis can be reproduced by openning `R_Assignment_Tuqa.Rmd` in RStudio and running all code chunks in order, or knittin the file to HTML. Running the analysis code will regenerate the files in `output/processed_files/` and `output/plots/`.
These regenerated files can be compared with the versions already included in the repository after downloading or cloning it from GitHub.
