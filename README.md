
# WGS Variant Interpretation of OCA Rare Condition Case Study

## Project Aim
This project focuses on analyzing whole genome sequencing (WGS) variants in the TYR gene associated with Oculocutaneous Albinism (OCA). Using public ClinVar data, the goal is to identify and interpret pathogenic variants to support clinical and genetic research applications.
# WGS Variant Interpretation of OCA Rare Condition Case Study

## Project Aim
This project focuses on analyzing whole genome sequencing (WGS) data to interpret genetic variants associated with Oculocutaneous Albinism (OCA), a rare genetic disorder. Specifically, variants in the **TYR** gene are filtered and classified based on clinical significance from the ClinVar database.

## Data Source
- The primary dataset is the **ClinVar Variant Summary** file obtained from the National Center for Biotechnology Information (NCBI) FTP server.
- URL: ftp://ftp.ncbi.nlm.nih.gov/pub/clinvar/tab_delimited/variant_summary.txt.gz

## Methods
- Downloaded and unzipped the full ClinVar variant summary file.
- Filtered for variants located in the TYR gene.
- Analyzed the filtered variants to identify those classified as pathogenic or likely pathogenic.
- Generated concise variant summaries including gene name, clinical significance, and associated phenotypes.
- Exported the final pathogenic variant list with summaries as a CSV file.

## Results
- Total variants found in the TYR gene: *[insert number from output]*.
- Pathogenic or likely pathogenic variants identified: *[insert number]*.
- The results provide insights into clinically relevant TYR gene variants implicated in OCA.

## How to Run
1. Open the Jupyter Notebook (`OCA_variant_analysis.ipynb`) in Google Colab or Jupyter environment.
2. Run all cells sequentially to download data, filter variants, and generate summary outputs.
3. The pathogenic variant summary CSV file (`TYR_pathogenic_variants_summary.csv`) will be saved in the working directory.
4. Review the results directly in the notebook or download the CSV for further analysis.

## Tools and Libraries
- Python (pandas, wget)
- Google Colab (optional, for cloud execution)

---

**Note:** This project demonstrates my capability to handle large genomic datasets, automate filtering and annotation processes, and generate meaningful biological insights in line with genome analyst roles.

