# SWYNEX-Biological-Dataset-Selection
Biological Dataset Selection using NCBI GEO
Task 1: Biological Dataset Selection
​1. Dataset Overview
​Dataset Title: Human Breast Tumor Cored Sample mRNA Array
​Organism: Homo sapiens (Human)
​Experiment Type: Expression profiling by array (mRNA gene expression analysis)
​Contributor / Organization: Kevin P. Claffey, UConn Health Center
​2. Public Repository & Source Details
​Repository: NCBI Gene Expression Omnibus (GEO)
GEO Accession ID: GSE38708
​BioProject ID: PRJNA168575
​Platform ID: GPL6104 (Illumina humanRef-8 v2.0 expression beadchip)
​Direct Source URL: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE38708
​3. Dataset Size & Structure
​Sample Cohort Size: 8 primary human breast cancer tissue samples (GSM948477 to GSM948484), with total RNA isolated from tumor-cell-dense regions of fresh-frozen primary breast cancer biopsies.
​Feature / Probe Count: ~22,184 probes per sample targeting RefSeq-curated human transcripts on the Illumina HumanRef-8 v2 BeadChip.
​File Sizes & Formats:
​GSE38708_RAW.tar: 3.4 MB (TAR archive of raw sample data)
​GSE38708_non-normalized.txt.gz: 2.1 MB (Compressed tab-delimited text file of non-normalized expression matrix)
​Series Matrix / SOFT / MINiML metadata files included.
​4. Research Question
​"Which specific mRNA transcripts and oncogenic signaling pathways show significant expression variability across tumor-cell-dense regions of primary human breast cancer cohorts, and how can these expression profiles help classify tumor heterogeneity or identify candidate prognostic biomarkers?"
​5. Selection Rationale & Downstream Utility
​GSE38708 provides a compact, well-annotated microarray expression dataset (8 primary tumor samples, ~3.4 MB raw archive) generated on the standardized Illumina humanRef-8 v2.0 platform. Its manageable size and clean tabular structure make it ideal for downstream preprocessing, normalization checks, and differential gene expression analysis without requiring heavy computational overhead.
