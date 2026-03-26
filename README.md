# Bridging Genetics and Precision Medicine in Parkinson’s Disease through GP2

`GP2 ❤️ Open Science 😍`

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19228213.svg)](https://doi.org/10.5281/zenodo.19228213)

**Last updated:** March 2026

## Summary


This is the online repository for the manuscript entitled **"Bridging Genetics and Precision Medicine in Parkinson’s Disease through GP2"**. This study focuses on **investigating potentially trial-eligible carriers of pathogenic and high-risk *GBA1* and *LRRK2* variants and conducting a global precision-medicine survey across GP2 sites**.

In this analysis, we screened sequencing and genotyping data (GP2 Release 11) from 65,509 individuals with Parkinson’s disease to identify and clinically characterize potentially trial-eligible carriers of pathogenic and high-risk *GBA1* and *LRRK2* variants. We further conducted a global precision-medicine survey across GP2 sites to evaluate their interest and capability to participate in precision medicine efforts and potential recruitment of individuals for clinical trials.

The notebooks provided here demonstrate how we extracted variant carriers and performed initial annotation across multiple ancestries using plink, bcftools, and annovar. It further includes a script on how to extract the corresponding clinical metadata for identified carriers. Finally, this repository provides the precision medicine survey questionnaire as well as the anonymized responses of GP2 sites.

## Data statement
Data used in the preparation of this article were obtained from the Global Parkinson’s Genetics Program (GP2; https://gp2.org).

All GP2 data are hosted in collaboration with the Accelerating Medicines Partnership in Parkinson’s disease, and are available via application on the website (https://amp-pd.org/register-for-amp-pd). For up-to-date information on GP2 data acquisition, access, and policies, visit https://gp2.org/. Tier 1 data can be accessed by completing a form on the Accelerating Medicines Partnership in Parkinson’s Disease (AMP®-PD) website (https://amp-pd.org/register-for-amp-pd). Tier 2 data access requires approval and a Data Use Agreement signed by your institution.

In this analysis we used Tier 2 GP2 Release 11 data ([10.5281/zenodo.17753486](https://doi.org/10.5281/zenodo.17753486)).

### Helpful Links

- [GP2 Website](https://gp2.org/)
  - [GP2 Cohort Dashboard](https://gp2.org/cohort-dashboard-advanced/)
- [Introduction to GP2](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.28494)
  - [Other GP2 Manuscripts (PubMed)](https://pubmed.ncbi.nlm.nih.gov/?term=%22global+parkinson%27s+genetics+program%22)

## Citation
*(pending publication)*

## Tables
*(pending publication)*

## Repository Orientation
- The `analysis/` directory includes all analyses discussed in the manuscript.

- Data extraction from the GP2 was performed using notebooks described previously in the code accompanying "Exploring the Global Landscape of Rare Causal and Common High-Risk Variants in Parkinson’s Disease" manuscript (https://github.com/GP2code/GP2-global-genetic-variant-landscape).

<pre> THIS_REPO/ 
  ├── analyses/ 
  |     └── 00_LRRK2_GBA_PM_github.ipynb
  ├── survey/
  |     ├── README.md
  |     ├── Precision_Medicine_Responses_2025_README.txt
  |     └── Precision_Medicine_Responses_2025.csv
  ├── LICENSE
  └── README.md 
</pre>

## Analysis Notebooks
### Languages: Python, bash, and R
| Directory | Notebooks   | Description | 
|-----------|----------------|--------|
|`analyses/`| `00_LRRK2_GBA_PM_github.ipynb`         | Clinical data summary |


## Software
| **Software** | **Version(s)** | **Resource URL** | **RRID** | **Notes** |
|--------------|----------------|------------------|----------|-----------|
|Python Programming Language|Python 3|http://www.python.org/|RRID:SCR_008394|pandas;numpy | Used for general dataframe manipulation|
