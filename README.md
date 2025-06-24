# CytoTRACE2 for Beginners  
*A simple guide to estimating cell potency from single-cell RNA-seq data*

This repository is intended for anyone, especially those with limited biology background who wants to explore **CytoTRACE2**, a tool that predicts how stem-like or differentiated a cell is using single-cell RNA-seq data.

These examples are based on the official [CytoTRACE2 GitHub](https://github.com/digitalcytometry/cytotrace2), with added explanations to help others like me who are new to this topic understand what's going on. 

> This project is a work in progress and will continue to improve as my understanding evolves.
---

## What is CytoTRACE2?

CytoTRACE2 is a deep learning model that uses gene expression data to estimate a cell's **potency**, i.e. how likely it is to be a stem-like or undifferentiated cell. It's useful for studying:
- How cells differentiate over time
- Tumor stemness
- Developmental processes

---

## What's in This Repository?

| File/Folder                  | Description |
|-----------------------------|-------------|
| `example_pancreas.ipynb`     | A Jupyter notebook that runs CytoTRACE2 on a mouse pancreas dataset. |
| `example_cordblood.ipynb`    | *(planned)* A notebook for applying CytoTRACE2 to human cord blood immune cells. |
| `immunogenicity_score.ipynb` | *(in preparation)* An exploratory notebook on how CytoTRACE2 scores may relate to immune marker expression. |
| `requirements.txt`           | Python dependencies to run the notebooks. |
                

---

## Getting Started

### 1. Clone this repo
```bash
git clone https://github.com/richcmwang/cytotrace2-for-beginners.git
cd cytotrace2-for-beginners
