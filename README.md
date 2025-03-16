# Glioblastoma Cell Types Analysis Using Single-Cell Sequencing

**Research on glioblastoma using single-cell sequencing in R programming.**

## Overview

This project focuses on analyzing single-cell RNA sequencing (scRNA-seq) data to identify and characterize different cell types present in glioblastoma tumors. Utilizing the Seurat package in R, the analysis includes data preprocessing, clustering, and visualization to gain insights into the cellular heterogeneity of glioblastoma.

## Project Structure

📁 **Glioblastoma-Cell-Types-using-Single-Cell**  
│-📂 **Data/**  
│      └── GSE84465_GBM_All_data.csv  
│-📂 **Image/**  
│      └── [Contains relevant images]  
│-📂 **Output Figures/**  
│      └── [Contains output figures from analysis]  
│-📜 **GBM_code.Rmd** (Main analysis script)  
│-📜 **Work_Poster.pdf** (Summary of research findings) 

## Analysis Workflow

1. **Data Loading**: Import the scRNA-seq dataset into a Seurat object.
2. **Quality Control**: Perform QC to filter out low-quality cells.
3. **Normalization**: Normalize the data for downstream analysis.
4. **Feature Selection**: Identify highly variable genes.
5. **Scaling**: Scale the data to ensure comparability.
6. **Dimensionality Reduction**: Apply PCA and UMAP for visualization.
7. **Clustering**: Cluster cells to identify distinct cell populations.
8. **Differential Expression**: Identify marker genes for each cluster.
9. **Visualization**: Generate plots to visualize clusters and marker genes.

## Dependencies

- R (version 4.0 or higher)
- Seurat
- dplyr
- patchwork
- ggplot2

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/royalseeker/Glioblastoma-Cell-Types-using-Single-Cell.git
    ```

2. Navigate to the project directory:
```bash
cd Glioblastoma-Cell-Types-using-Single-Cell
```

3. Open the GBM_code.Rmd file in RStudio.
4. Install the required R packages if not already installed:
```R
    install.packages(c("Seurat", "dplyr", "patchwork", "ggplot2"))
``` 
5. Run the code chunks in GBM_code.Rmd to reproduce the analysis.

Results

The analysis led to the identification of various cell populations within glioblastoma tumors, each characterized by unique gene expression profiles. Detailed results and visualizations are available in the output figures directory and the Work_Poster.pdf file.
