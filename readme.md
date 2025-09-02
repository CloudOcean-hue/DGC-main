# Disentangled Information Quantification for Dataset Construction in Data-Centric AI

This repository will provide the official implementation of our paper:  
**"Disentangled Information Quantification for Dataset Construction in Data-Centric AI"** *(under review)*.

---

## 🔍 Overview

Recent advances in AI emphasize that **data quality and structure are as critical as model capacity**, motivating the paradigm of **Data-Centric AI (DCAI)**. However, most existing dataset construction methods rely on **model-dependent active learning criteria**, tightly coupling sample selection to specific architectures and training dynamics, which limits transferability.  

We introduce **Disentangled Generalizable Construction (DGC)**, a **model-agnostic framework** for informative data selection.  
DGC is built upon three key components:

1. **OF-SQAE**  
   A disentangled representation model that integrates orthogonal non-negative matrix factorization with soft quantization to obtain stable and interpretable semantic factors.

2. **IAIQ**  
   A theoretical framework that quantifies sample informativeness in the latent space, enabling principled evaluation of data quality.

3. **DGC**  
   A coverage-driven greedy algorithm that selects representative subsets with high semantic coverage, ensuring that the constructed dataset effectively represents diverse modalities and variations.

---

## 📌 Key Features (Coming Soon)

- Implementation of **OF-SQAE** for learning disentangled semantic representations.  
- Open-source code for **IAIQ** to measure dataset informativeness.  
- Reproducible pipelines for **DGC** to construct compact yet highly informative datasets.  
- Experiments validating disentanglement capability on synthetic datasets and generalization performance on natural image benchmarks.  

---

## 📖 Paper

> *Disentangled Information Quantification for Dataset Construction in Data-Centric AI*  
> *(Currently under peer review — preprint coming soon)*

---

## 🚧 Project Status

This repository is currently **under development**.  
Code for OF-SQAE, IAIQ, and DGC will be released after the review process.  
**Note: This work focuses on methodology and theory; pretrained models will not be provided.**

---

## 📜 License

The code will be released under an **open-source license** upon publication.  
Please check back later for details.
