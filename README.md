# Novel Parkinson’s Disease Genetic Risk Factors Within and Across European Populations

`GP2 ❤️ Open Science 😍`

Pending DOI 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Last Updated:** March 2025

## Summary
This is the online repository for the short report titled ***"Novel Parkinson’s Disease Genetic Risk Factors Within and Across European Populations"***. This study presents the largest meta-analysis of Parkinson’s disease genetic risk to date, incorporating data from over 64,000 cases, 17,700 proxy cases, and 1.75 million controls across diverse European ancestries (Finnish, Icelandic, Ashkenazi, and broadly European). By identifying 134 risk loci, including 59 novel ones, and integrating multi-omic data, we provide new insights into the genetic architecture of Parkinson’s disease, highlighting key genes and pathways for future research and therapeutic development.

## Citation
If you use this repository or find it helpful for your research, please cite the corresponding manuscript:

> Novel Parkinson’s Disease Genetic Risk Factors Within and Across European Populations (Global Parkinson's Genetics Program, 2025)
>> Manuscript DOI: coming soon
>>  GitHub DOI: coming soon

### Data Statement 
* All GP2 data are hosted in collaboration with the Accelerating Medicines Partnership in Parkinson's Disease (AMP-PD) and are available via application on the website. The GP2 PD case and control data are available via the GP2 analysis platform (https://gp2.org; release 9: 10.5281/zenodo.14510099). 
* Genotyping imputation, quality control, ancestry prediction, and processing were performed using GenoTools (v1.0.0), publicly available on GitHub
* Summary statistics from the Million Veteran's Program were made available through a collaboration, apply for access here: https://www.mvp.va.gov/pwa/mvp-data-available-research
* Analyses conducted on the UKBiobank were performed on the DNANexus platform, apply for access here: https://www.ukbiobank.ac.uk/enable-your-research/apply-for-access


### Helpful Links 
- [GP2 Website](https://gp2.org/)
    - [GP2 Cohort Dashboard](https://gp2.org/cohort-dashboard-advanced/)
- [Introduction to GP2](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.28494)
    - [Other GP2 Manuscripts (PubMed)](https://pubmed.ncbi.nlm.nih.gov/?term=%22global+parkinson%27s+genetics+program%22)



# Repository Orientation 
- The `analyses/` directory includes all analyses discussed in the manuscript

```
├── LICENSE.txt
├── README.md
└── analyses
    ├── FUMA.ipynb
    ├── METAL.ipynb
    ├── OR_and_forest_plot.ipynb
    ├── PoPS.ipynb
    └── meta_GWASes.ipynb
```

---
### Analysis Notebooks
* Languages: Python, bash, and R

| Directory  | Notebooks                | Description                                                                       |
|------------|--------------------------|-----------------------------------------------------------------------------------|
| xx/    | 01_xx    | xx    |



---

# Software 
|               Software              |  Version(s) |                              Resource URL                              |       RRID      |                                               Notes                                               |   |
|:-----------------------------------:|:-----------:|:----------------------------------------------------------------------:|:---------------:|:-------------------------------------------------------------------------------------------------:|:-:|
|     Python Programming Language     | 3.9 and 3.10 |                         http://www.python.org/                         | RRID:SCR_008394 | pandas; numpy; seaborn; matplotlib; statsmodel; used for general data wrangling/plotting/analyses |   |
| R Project for Statistical Computing |     4.2     |                        http://www.r-project.org/                       | RRID:SCR_001905 |   tidyverse; dplyr; tidyr; ggplot; data.table; used for general data wrangling/plotting/analyses  |   |
|                PLINK                |     2.0 and 1.9    |                   http://www.nitrc.org/projects/plink                  | RRID:SCR_001757 |                                     used for genetic analyses                                     |   |
| ANNOVAR | 2020-06-08 | http://www.openbioinformatics.org/annovar/	| RRID:SCR_012821 | Genetic annotation software |
|                METAL                |      2020-05-05     |         http://csg.sph.umich.edu//abecasis/Metal/        | RRID:SCR_002013 |                                       used for averaging effect allele frequency in meta-analyses                                      |
| LDSC | 1.0.1 | https://github.com/bulik/ldsc | RRID:SCR_022801 | used for estimating heritability and genetic correlation | 
