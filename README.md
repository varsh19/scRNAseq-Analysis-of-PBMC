# Single-cell RNA-seq Analysis of the PBMC Dataset from 10x Genomics

In this project, a basic single-cell RNA-seq analysis to identify cell types from a given dataset was performed.

## Dataset Used

PBMC (Peripheral Blood Mononuclear Cells) are a type of blood cell that is critical to the immune system. This group consists of lymphocytes (such as T cells, B cells, and NK cells) and monocytes, and sometimes include dendritic cells. PBMCs are used extensively in research to study immune responses and various diseases, including infections, cancer, and autoimmune disorders.

In single-cell RNAseq studies, PBMCs are often analyzed to identify different cell types and states, study their gene expression profiles, and understand their roles in immune responses. The PBMC datasets, like this one from 10x Genomics (pbmc3k), are commonly used as benchmarks and for developing and testing computational methods in scRNA-seq analysis.

## Steps Performed

### 1. Preprocessing
  * Performed quality control (filtering cells and genes)
  * Normalized the data
  * Identified highly variable genes

### 2. Dimensionality Reduction
  * Performed PCA (Principal Component Analysis)
  * Visualized the first two principal components

### 3. Clustering
  * Applied the Louvain clustering algorithm
  * Visualized the clusters using UMAP

### 4. Cell Type Annotation
  * Identified marker genes for each cluster
  * Annotated clusters with potential cell types based on marker genes

### 5. Differential Expression Analysis
  * Performed differential expression analysis between identified clusters
