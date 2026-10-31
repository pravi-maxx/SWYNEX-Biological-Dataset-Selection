# SWYNEX-Biological-Dataset-Selection
Biological Dataset Selection using NCBI GEO
# Task 1: Biological Dataset Selection

## 📋 Project Overview

This repository contains the documentation and dataset selection for Task 1 of the SWYNEX Bioinformatics Internship. The objective of this task is to select a public biological/genomic dataset, define its key characteristics, and outline a research question for downstream computational analysis.

---

## 🧬 Dataset Details

* **Dataset Title:** Human Breast Tumor Cored Sample mRNA Array
* **Organism:** *Homo sapiens* (Human)
* **Experiment Type:** Expression profiling by array (mRNA gene expression)
* **Public Repository:** NCBI Gene Expression Omnibus (GEO)
* **GEO Accession ID:** `GSE38708`
* **BioProject ID:** `PRJNA168575`
* **Platform ID:** `GPL6104` (Illumina humanRef-8 v2.0 expression beadchip)
* **Direct Dataset URL:** [https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE38708](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE38708)

---

## 📊 Dataset Size & File Structure

| Parameter | Details |
| :--- | :--- |
| **Sample Size** | 8 primary human breast cancer tissue samples (`GSM948477` – `GSM948484`) |
| **Feature Count** | ~22,184 probes per sample (RefSeq-curated human transcripts) |
| **Raw Data Archive** | `GSE38708_RAW.tar` (3.4 MB) |
| **Matrix File** | `GSE38708_non-normalized.txt.gz` (2.1 MB compressed tab-delimited text) |
| **Metadata Format** | SOFT, MINiML, and Series Matrix files |

---

## 🔬 Research Question

> *"Which specific mRNA transcripts and oncogenic signaling pathways exhibit significant expression variability across tumor-cell-dense regions of primary human breast cancer samples, and how can these expression signatures be leveraged to identify candidate diagnostic or prognostic biomarkers?"*

---

## 💡 Rationale for Selection

1. **High-Quality Curation:** Hosted on NCBI GEO with standardized Illumina BeadChip probe annotations (`GPL6104`).
2. **Computational Efficiency:** With 8 samples and a compact file size (~3.4 MB raw archive), it allows rapid quality control, normalization, and differential expression analysis.
3. **Clinical Relevance:** Captures gene expression directly from tumor-cell-dense breast cancer biopsies, providing meaningful biological insights into tumor heterogeneity.
4.
