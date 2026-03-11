# BF550 Final project

### Assignment Guidelines
Choose a paper and reproduce at least two of its figures. As a rough guide, reproducing one figure that involves p-values and one figure that involves PCA or clustering is an appropriate amount of work when starting with processed data.

### Project Overview
I elected to reproduce figures from a 2025 paper by Gao et al. investigating prognostic indicators of endometrial carcinoma (EC) [1]. Specifically, the analysis focuses on reproducing:
1. A principal component analysis (PCA) used to visualize separation between metastatic and non-metastatic samples based on gene expression profiles.
2. A volcano plot showing fold change and statistical significance for differentially expressed genes.

This repo contains:
- **`preprocess.Rmd`** – preprocessing of microarray expression data and differential expression analysis  
- **`report.ipynb`** – recreation of figures and the complete project report

### Reference
[1] Gao, L., Yuan, D., Huang, A., & Qian, H. (2025). Bioinformatics-based identification of differentially expressed genes in endometrial carcinoma: Implications for early diagnosis and prognostic stratification. Frontiers in Genetics, 16, Article 1631060. https://doi.org/10.3389/fgene.2025.1631060