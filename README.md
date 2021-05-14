# PCA practive

## What are these data and codes?
This page contains the dataset and codes to practice PCA using R. Since we are pretty much familiar with genotype PCA, I prepared genotype data of 1KG Phase 3 (only Chr1 for computational efficiency). Thus, we can easily understand whether or not our PCA outputs makes sense or not.

## Plink outputs
We are also familiar with Plink outputs. Let's use it as a gold standard in this page.

## Jupyter notebook (R codes)
- demo01_center_scaling.ipynb: This script was provided to understand how centering and scaling is critical for PCA. Centering is always important. Scaling is especially important when you have rare variants.
- demo02_pca_from_grm.ipynb: We usually calculate PCs from SNP-SNP covariance matrix (I believe this is the typical approach of PCA analysis). However, some researchers calculate PCs from Sample-Sample covariance matrix (i.e. GRM). I wrote this script to understand this gap. 

