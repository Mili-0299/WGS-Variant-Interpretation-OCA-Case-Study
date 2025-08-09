
# WGS Variant Interpretation of OCA Rare Condition Case Study

## Project Aim
This project focuses on analyzing whole genome sequencing (WGS) variants in the TYR gene associated with Oculocutaneous Albinism (OCA). Using public ClinVar data, the goal is to identify and interpret pathogenic variants to support clinical and genetic research applications.

## Data Source
- Variant summary data downloaded from [NCBI ClinVar FTP](ftp://ftp.ncbi.nlm.nih.gov/pub/clinvar/tab_delimited/variant_summary.txt.gz)
- Filtered to include only variants related to the TYR gene.

## Methods
- Download and preprocess ClinVar variant summary data.
- Filter for variants mapped to the TYR gene.
- Extract variants classified as 'Pathogenic' or 'Likely pathogenic.'
- Annotate genomic positions and clinical significance.
- Generate a summarized report of clinically relevant variants.
- Implemented in Python using pandas for data manipulation.

## Usage
- The analysis is provided as a Jupyter notebook (`WGS_OCA_variant_interpretation.ipynb`).
- Run the notebook on Google Colab or any Jupyter environment.
- Outputs include a CSV file summarizing pathogenic TYR variants (`TYR_pathogenic_variants_summary.csv`).

## Expected Results
A detailed list of clinically significant variants in the TYR gene linked to OCA, supporting variant interpretation workflows in genomic diagnostics.

