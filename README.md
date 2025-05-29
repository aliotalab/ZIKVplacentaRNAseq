# ZIKVplacentaRNAseq
This repository contains all of the R and Bash scripts used to generate the figures in Bohm et al. 2025 (Journal of Virology DOI: DOI: 10.1128/jvi.00666-25). Many of the code chunks were adapted from Berry et al. 2021 (DOI: 10.1128/mBio.01214-21).

Step 0: RNAseq fastq files were first mapped to the Mus musculus genome using Kallisto.

Step 1-6 detail the code used to process kallisto-aligned RNAseq data, determine average differential gene expression for each inoculation, construct volcano plots, and conduct gene set enrichment analysis (GSEA). These types of plots are shown in Figures 3-5 of the manuscript. For the ease of the reader, code is shown for the E9.5 placenta (aka chorion) dataset that includes PBS-, 10^3 PFU ZIKV-MEX-, and 10^3 PFU ZIKV-BRA-inoculated groups. At E11.5, the decidua and placenta were examined (separately), and additional pairwise comparisons were made with the 10^5 PFU ZIKV-MEX-inoculated group. The code template published here was followed for all RNAseq data analysis in this manuscript. 

Additional code for Figures 6 and 8 are shown within their respective files. 
