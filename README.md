# PCA practive

## What are these data and codes?
This page contains the dataset and codes to practice PCA using R. Since we are ver familiar with genotype PCA, I prepared genotype data of 1KG Phase 3 (only Chr1 for computational efficiency). Thus, we can easily understand whether or not our PCA outputs make sense or not.


## Jupyter notebook (R codes)
- demo01_center_scaling.ipynb: This script was provided to understand how centering and scaling is critical for PCA. I found that centering is always important. Scaling is especially important when you have rare variants.

- demo02_pca_from_grm.ipynb: We usually calculate PCs from SNP-SNP covariance matrix (I believe this is the typical approach of PCA analysis). However, some researchers calculate PCs from Sample-Sample covariance matrix (i.e. GRM). Why is it? How are they different? I wrote this script to understand this gap. Interestingly, I found that "PC scores" from SNP-SNP matrix is identical as "eigenvectors" from Sample x Sample matrix. Usually, the number of SNPs is much larger than the number of samples, the strategy using Sample x Sample matrix (GRM) is computationally very efficient. If you have any comments, please let me know. 


## Plink outputs
We are also familiar with Plink outputs. Let's use them as a gold standard in this page.


