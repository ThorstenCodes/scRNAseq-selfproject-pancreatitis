# Single-Cell RNA-seq Analysis of Mouse Dataset with scvi-tools  

This repository contains a Jupyter Notebook demonstrating an independent **re-analysis of a publicly available mouse single-cell RNA-seq (scRNA-seq) dataset**.  
The aim is **not to reproduce the original publication**, but to showcase skills in **single-cell data processing, integration, annotation, and functional interpretation** using state-of-the-art computational tools.  

---

## 📌 Key Features  

- **Data Processing & QC**  
  - Filtering of cells and genes (UMIs, mitochondrial content, etc.)  
  - Normalization and preprocessing  

- **Integration & Modeling**  
  - Batch integration using **[scvi-tools](https://scvi-tools.org/)**  
  - Dimensionality reduction and clustering  
  - Subclustering for higher-resolution insights  

- **Cell Type Identification**  
  - Marker gene visualization and selection  
  - Identification of **acinar-to-ductal metaplasia (ADM) cells** and other populations  
  - Validation of subcluster groups with known markers  

- **Pathway & Functional Analysis**  
  - **Gene Set Enrichment Analysis (GSEA)**  
  - Overrepresentation Analysis (ORA)  
  - **Gene Set Scoring** for biological programs (e.g., proliferation, stress, differentiation)  
  - Cluster-specific and inter-cluster comparisons  

---

## 🧪 Biological Focus  

- Exploration of **ADM-associated cell states**  
- Annotation of all major epithelial and stromal populations  
- Functional interpretation of cluster-specific and cell state–specific gene programs  

---

## ⚙️ Tools & Technologies  

- **Python** (Jupyter Notebook)  
- **scvi-tools** (probabilistic modeling & batch integration)  
- **Scanpy / AnnData** (single-cell analysis & visualization)  
- **GSEApy** (GSEA and ORA)  
- **matplotlib / seaborn** (custom plots)  

---

## 📂 Repository Structure  

```bash
.
├── notebook.ipynb         # Main analysis notebook
├── requirements.txt       # Python packages needed to run the notebook
└── README.md              # Project overview
```

## 🚀 Install Requirements

Install all packages used in this notebook with a single command:

```bash
pip install -r requirements.txt
```
    ⚠️ Note: Some packages may also include inline !pip install ... commands directly in notebook cells if needed.

## 📖 Dataset Information  

The dataset analyzed in this notebook originates from:  

**Poggetto E; Ho I et al. Science, 2025. PMID: 34529467**  

- GEO accession: **[GSE181276](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE181276)**  
- Individual dataset: **GSM5494073**  

Instructions for downloading and preparing the dataset are provided directly in the notebook.  

---

## 🧑‍💻 Author  

- Thorsten Kaltenbacher – aspiring bioinformatician transitioning from wet-lab to computational biology.  

