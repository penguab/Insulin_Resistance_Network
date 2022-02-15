# Insulin-Resistance-Networks

This directory contains the MEGENA co-expression networks and Bayesian networks for adipose and muscle tissues of AAGMEx and METSIM databases. The donor age, sex, and ethnic groups were adjusted before network construction. 

Author: Peng Xu

Email: peng.xu@mssm.edu

Draft date: Feb 11, 2022

## Description

The co-expression networks for different tissues were uniformly processed by the MEGENA pipeline. The gene expressions were generated from the normalized microarray datasets from different resources. 

For each tissue, four files were shared for the network results.

{Population}_{tissue}_network.tsv: The MEGENA co-expression network for each tissue.

{Population}_{tissue}_bigtable.tsv: The module summary information for the co-expression network.

{Population}_{tissue}_module.tsv: The module genes for the co-expression network.

{Population}_{tissue}_Bayesian.tsv: The Bayesian network for each tissue.

ARmuscleRNAseqBGI_135_sample-Normalized_Count-DESeq2_with_annot.txt.gz: Muscle RNA-seq with normalized read counts in the Arkansas cohort.

ArkansasND_Cohort-phenotype_data-FinalSept2009.txt: Meta file for muscle RNA-seq in the Arkansas cohort.

## Citation

## News

2/11/2022: First version released.

