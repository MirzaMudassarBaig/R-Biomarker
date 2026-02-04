# R-Biomarker: Cervical Cancer Pipeline (GSE63514 + TCGA-CESC) — ANO10 Study

[![R](https://img.shields.io/badge/R-4.5.1-blue)](https://www.r-project.org/) [![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

This repository contains an **R-based biomarker identification pipeline** for cervical cancer transcriptomics. It integrates **GSE63514 (GEO microarray)** and **TCGA-CESC (RNA-seq)** datasets, focusing on **differential expression analysis, functional enrichment, ANO10 co-expression**, and **immune checkpoint analysis**.

---

## 🔹 Features

- Preprocess and normalize **TCGA-CESC RNA-seq counts** (DESeq2).  
- Download and analyze **GSE63514 microarray data**.  
- Perform **DEG analysis (Cancer vs Normal)** using **limma**.  
- Annotate probes to **gene symbols and Entrez IDs**.  
- Conduct **GO BP & KEGG pathway enrichment** for up- and down-regulated genes.  
- Identify **overlapping DEGs** between GSE63514 and TCGA-CESC.  
- Compute **ANO10 co-expression** and visualize top correlated genes.  
- Compare **immune checkpoint gene expression** between ANO10-High vs ANO10-Low groups.  

---

## 🔹 Project Structure

