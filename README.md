# 16S-rRNA-Microbiome-Analysis-
using nf-core/ampliseq pipeline
Microbiome Analysis Project (nf-core/ampliseq)

**Overview**

This project analyzes 16S rRNA sequencing data using nf-core/ampliseq pipeline.

*Tools Used*
nf-core/ampliseq
/n QIIME2
/n DADA2
/n Docker

*Data*
Input: 
/n FASTQ file (single sample)
Output:
/n ASV table, taxonomy table, abundance plots

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
