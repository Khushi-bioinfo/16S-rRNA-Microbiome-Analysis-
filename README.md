# 16S-rRNA-Microbiome-Analysis-
using nf-core/ampliseq pipeline
Microbiome Analysis Project (nf-core/ampliseq)
 Overview

This project analyzes 16S rRNA sequencing data using nf-core/ampliseq pipeline.

*Tools Used*
nf-core/ampliseq
QIIME2
DADA2
Docker

*Data*
Input: FASTQ file (single sample)
Output: ASV table, taxonomy table, abundance plots

*Workflow Steps*
Quality control (FastQC)
Denoising (DADA2)
Taxonomy assignment (SILVA database)
Abundance calculation
Visualization (barplots)

*Results*

Dominant genera:

1. Bacteroides
2. Prevotella
3. Blautia
Faecalibacterium
