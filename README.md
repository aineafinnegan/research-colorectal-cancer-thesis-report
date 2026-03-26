# research-colorectal-cancer-thesis
MSc thesis on Fusobacterium nucleatum-induced transcriptomic responses in colorectal cancer subtypes using RNA-seq, differential expression analysis, GSEA, and pathway enrichment.
# Mapping microbiome-induced host transcriptomic interactions in colorectal cancer

MSc thesis project investigating how *Fusobacterium nucleatum* influences subtype-specific transcriptomic responses in colorectal cancer models.

## Overview
This project explores how *Fusobacterium nucleatum* subsp. *nucleatum* affects gene expression in colorectal cancer cell lines representing different Consensus Molecular Subtypes (CMS). The study focuses on HT-29 and MDST8 models, used here as CMS1-like and CMS4-like systems, to examine whether microbial exposure produces shared or subtype-specific transcriptional responses.

## Research question
How does *Fusobacterium nucleatum* alter host transcriptomic programmes across distinct colorectal cancer molecular subtypes?

## Aims
- Evaluate transcriptomic changes induced by *F. nucleatum* infection in HT-29 and MDST8 colorectal cancer cell lines
- Identify shared and subtype-specific differentially expressed genes
- Assess functional relationships using protein-protein interaction analysis
- Investigate affected pathways using Gene Set Enrichment Analysis (GSEA) and exploratory KEGG analysis

## Methods
- In vitro infection of HT-29 and MDST8 colorectal cancer cell lines
- Validation using MTT assays, PCR, and qPCR
- RNA-seq data processing with `nf-core/rnaseq`
- Differential expression analysis with `DESeq2` and `edgeR`
- Principal component analysis (PCA)
- STRING protein-protein interaction analysis
- GSEA and KEGG pathway enrichment analysis
- Visualisation in R using packages including `ggplot2`, `ggrepel`, and `pheatmap`

## Key findings
- HT-29 showed a broader transcriptional response to *F. nucleatum* infection than MDST8
- 18 significantly altered genes were identified in HT-29 and 4 in MDST8
- `DUSP1` was the only gene downregulated in both models
- HT-29 showed enrichment of translation- and ribosome-related pathways
- MDST8 showed enrichment in transcription factor and microRNA target gene sets
- The findings support both divergent and shared transcriptional responses across colorectal cancer subtypes

## Repository contents
- Thesis PDF
- Figures and written analysis from the final MSc project

## Tools and technologies
- R
- RNA-seq
- DESeq2
- edgeR
- GSEA
- KEGG pathway analysis
- STRING
- Bioinformatics workflows

## Note
This repository contains the final thesis document only. Raw sequencing data and any restricted research materials are not included.
