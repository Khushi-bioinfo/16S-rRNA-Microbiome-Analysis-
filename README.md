# 16S-rRNA-Microbiome-Analysis-
using nf-core/ampliseq pipeline
Microbiome Analysis Project (nf-core/ampliseq)

**Overview**

This project analyzes 16S rRNA sequencing data using nf-core/ampliseq pipeline.

*Tools Used*
1. nf-core/ampliseq
2. QIIME2
3. DADA2
4. Docker

*Data*
Input: 
FASTQ file (single sample)
Output:
1. ASV table
2. Taxonomy table
3. Abundance plots

*Workflow Steps*
1. Quality control (FastQC)
2. Denoising (DADA2)
3. Taxonomy assignment (SILVA database)
4. Abundance calculation
5. Visualization (barplots)

*Results*

Dominant genera:

1. Bacteroides
2. Prevotella
3. Blautia
4. Faecalibacterium
