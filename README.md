# 📊 VQA Dataset EDA & Analysis
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Thanmai-11/vqa-dataset-eda/blob/main/notebooks/eda_all_vqa_datasets.ipynb)

This repository contains detailed **Exploratory Data Analysis (EDA)** for multiple Visual Question Answering (VQA) datasets spanning general, medical, and botanical domains. The goal is to analyze the linguistic, semantic, and structural characteristics of each dataset to inform model design, domain adaptation, and benchmarking.

---

## 📁 Datasets Analyzed

| Dataset              | Domain     | # Images | # QA Pairs | Description                                |
|----------------------|------------|----------|------------|--------------------------------------------|
| **Easy-VQA**         | General    | 4,000    | 48,248     | Synthetic geometric images with simple Yes/No and spatial QA pairs |
| **PathVQA**          | Medical    | 4,998    | 32,632     | Pathology textbook images and factual questions |
| **VQA-RAD**          | Medical    | 315      | 2,244      | Radiology images (CT, X-ray, MRI) with clinician-authored QA pairs |
| **Botany-VQA**       | Botanical  | 2,000    | 12,000 / 52,000 | Custom dataset over Oxford Flowers 102 with factual and free-form QA pairs |

---


This Jupyter notebook includes:

- Dataset summary and loading
- Distribution of question lengths
- Answer frequency distributions
- Unique answer classes per dataset
- Comparison of curated vs merged Botany-VQA
- Insights on domain bias and class imbalance





