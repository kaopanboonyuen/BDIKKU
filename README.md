# 🧬 BDI Young Innovator Hackathon 2026
# AI for Phenome × DNA × Health Intelligence

🎓 **Big Data Institute (BDI) x Khon Kaen University (KKU)**  
🚀 National Youth Innovation Hackathon Program  
🧠 From Genomics → Phenomics → Explainable Healthcare AI  
💡 Building Data-Driven Systems for Next-Generation Precision Medicine

---

## 👨‍💻 Author

**Teerapong Panboonyuen, Ph.D. (P'Kao)**  
📍 Chulalongkorn University, Thailand  
📫 `teerapong [dot] pa [at] chula [dot] ac [dot] th`

🌐 Repository  
https://github.com/kaopanboonyuen/BDIKKU

---

## 👨‍🏫 Lecture Materials

📄 Lecture Slides  
[![View Lecture Slides](https://img.shields.io/badge/View-Lecture_Slides-red?style=for-the-badge)](https://github.com/kaopanboonyuen/BDIKKU/blob/main/slides/BDIKKU_HackathonAI_PanboonyuenLecture.pdf)

📓 Google Colab Notebook (Student Version)  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kaopanboonyuen/BDIKKU/blob/main/notebooks/BDIKKU_Hackathon_AI_for_Phenome_DNA_and_Health_toStudent.ipynb)

---

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green.svg)
![XGBoost](https://img.shields.io/badge/XGBoost-GradientBoosting-orange.svg)
![Genomics](https://img.shields.io/badge/Genomics-DNA-red.svg)
![Healthcare AI](https://img.shields.io/badge/Healthcare-AI-purple.svg)
![Explainable AI](https://img.shields.io/badge/XAI-SHAP-yellow.svg)
![License](https://img.shields.io/badge/License-Educational-lightgrey.svg)

---

# 🌎 Overview

Welcome to the official repository for:

> **AI for Phenome × DNA × Health Intelligence**
>
> *Building Data-Driven Systems for Next-Generation Healthcare & Intelligent Living*

Artificial Intelligence is rapidly transforming healthcare, biotechnology, and precision medicine.

Modern health intelligence systems no longer rely solely on clinical measurements.

Instead, they integrate multiple layers of biological information:

- 🧬 Genomics (DNA)
- 📊 Phenomics (Observable traits)
- 🏥 Clinical Data
- 📈 Longitudinal Health Records
- 🤖 Machine Learning Models
- 🔍 Explainable AI

This hackathon introduces students to the entire pipeline of biomedical AI through two real-world challenges:

### Challenge 1 — DNA Sequence Classification
Learn how machine learning can understand biological sequences and identify gene families directly from DNA.

### Challenge 2 — Heart Attack Risk Prediction
Build predictive healthcare models capable of identifying cardiovascular risk using phenomic data.

By combining genomics, phenomics, machine learning, and explainable AI, participants will experience how modern precision medicine systems are designed in academia, hospitals, and biotech industries.

---

# 🚀 Why This Hackathon Matters

The future of healthcare is becoming increasingly data-driven.

Today's biomedical researchers and AI engineers must understand how to:

- Extract knowledge from DNA sequences
- Build predictive healthcare systems
- Interpret black-box machine learning models
- Handle imbalanced medical datasets
- Design trustworthy AI for clinical decision support

The concepts taught in this workshop directly connect to:

- 🧬 Precision Medicine
- 🧫 Bioinformatics
- ❤️ Digital Health
- 🏥 Clinical AI
- 🧠 Explainable Machine Learning
- 📈 Population Health Analytics
- 🚀 Biomedical Innovation

---

# 🏗️ Repository Structure

```bash
BDIKKU/
│
├── slides/
│   └── BDIKKU_HackathonAI_PanboonyuenLecture.pdf
│
├── notebooks/
│   └── BDIKKU_Hackathon_AI_for_Phenome_DNA_and_Health_toStudent.ipynb
│
├── Dataset/
│   ├── DNA_Sequence_Dataset/
│   └── Heart_Attack/
│
└── README.md
```

---

# 📘 Lecture Topics

## 🌱 Part 0 — Foundations of Health Intelligence

Before building AI systems, students will learn:

### 🧬 What is DNA?

Understanding:

- Nucleotides (A, T, C, G)
- Genes
- Proteins
- Gene Families
- Biological Information Encoding

### 📊 What is the Phenome?

Understanding:

- Observable biological traits
- Clinical measurements
- Vital signs
- Laboratory values
- Disease phenotypes

### 🤖 Why AI for Healthcare?

Understanding how machine learning enables:

- Risk prediction
- Early diagnosis
- Precision medicine
- Clinical decision support

---

# 🧬 Challenge 1 — DNA Sequence Intelligence

## Problem Statement

Given a raw DNA sequence:

```text
ATGCCCCAACTAAATACCGCCGTATGACCC...
```

Predict which gene family it belongs to.

---

## What Students Will Learn

### 🔍 Exploratory Data Analysis (EDA)

- Sequence length analysis
- GC-content analysis
- Species comparison
- Class imbalance inspection

---

### 🧪 Feature Engineering

Transform biological sequences into machine-readable features using:

### k-mer Encoding

```text
DNA Sequence
      ↓
k-mer Extraction
      ↓
Frequency Features
      ↓
Machine Learning
```

Topics:

- Biological sequence representation
- NLP-inspired genomic features
- High-dimensional feature engineering

---

### 🌐 Dimensionality Reduction

Visualize biological patterns using:

- PCA
- UMAP

Students will discover hidden structures inside genomic data.

---

### ✂️ Feature Selection

Learn why not all DNA patterns matter.

Methods:

- LASSO (L1 Regularization)
- Sparse Learning
- Feature Importance Analysis

---

### 🏆 Machine Learning Models

Students will compare:

| Model | Application |
|---------|------------|
| XGBoost | Main benchmark |
| LightGBM | Fast boosting |
| CatBoost | Robust boosting |
| Random Forest | Classical ensemble |

---

### 🔍 Explainable AI

Using SHAP:

- Interpret model decisions
- Discover influential DNA motifs
- Understand biological relevance

---

# ❤️ Challenge 2 — Heart Attack Risk Prediction

## Problem Statement

Using patient clinical information:

- Age
- Blood Pressure
- Cholesterol
- ECG Results
- Heart Rate
- Exercise Indicators

Predict:

```text
High Risk
or
Low Risk
```

for heart attack occurrence.

---

## What Students Will Learn

### 📊 Medical Data Exploration

Understand:

- Patient demographics
- Clinical measurements
- Disease prevalence
- Healthcare datasets

---

### ⚖️ Class Imbalance Handling

Real healthcare data is rarely balanced.

Students will explore:

- Class weighting
- SMOTE
- Evaluation metrics beyond accuracy

---

### 🏥 Clinical Machine Learning

Train predictive models using:

- Logistic Regression
- XGBoost
- LightGBM
- CatBoost
- Random Forest

---

### 🔬 Explainable Healthcare AI

Interpret predictions using:

- SHAP
- Permutation Importance
- Feature Attribution

Because in healthcare:

> Accuracy alone is not enough.
>
> Trust and interpretability matter.

---

### ⏳ Survival Analysis

Introduction to:

### Cox Proportional Hazards Model

Applications:

- Patient prognosis
- Disease progression
- Risk stratification

A foundational concept in modern medical AI research.

---

# 🧠 Core Concepts Covered

Throughout the workshop students will encounter:

| Domain | Concepts |
|----------|-----------|
| Genomics | DNA, k-mers, gene families |
| Bioinformatics | Sequence analysis |
| Machine Learning | Classification |
| Explainable AI | SHAP |
| Healthcare AI | Clinical prediction |
| Statistics | Survival analysis |
| Data Science | EDA, visualization |
| Feature Engineering | Selection & transformation |
| Biomedical Informatics | Genomics + Phenomics integration |

---

# 🎯 Learning Outcomes

By the end of this hackathon, participants will be able to:

✅ Build machine learning pipelines for biological data

✅ Transform DNA sequences into predictive features

✅ Train state-of-the-art gradient boosting models

✅ Apply explainable AI techniques

✅ Predict clinical outcomes from phenomic data

✅ Understand the foundations of precision medicine

✅ Analyze healthcare datasets responsibly

✅ Present AI solutions for biomedical innovation

---

# 🚀 Getting Started

## 1️⃣ Clone Repository

```bash
git clone https://github.com/kaopanboonyuen/BDIKKU.git

cd BDIKKU
```

---

## 2️⃣ Open Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kaopanboonyuen/BDIKKU/blob/main/notebooks/BDIKKU_Hackathon_AI_for_Phenome_DNA_and_Health_toStudent.ipynb)

---

## 3️⃣ Run the Workshop Notebook

The notebook contains:

- Theory
- Coding Exercises
- Visualizations
- Challenges
- Leaderboards
- Hackathon Tasks

All runnable directly in Google Colab.

---

# 🏆 Final Hackathon Challenge

Students will form teams and design their own AI solution using:

### 🧬 Genomic Features

and/or

### ❤️ Clinical Phenomic Features

Participants are encouraged to:

- Improve feature engineering
- Optimize models
- Increase interpretability
- Discover novel insights
- Build impactful healthcare solutions

---

# 🌟 Educational Philosophy

This workshop is intentionally designed beyond typical classroom examples.

Students will learn not only:

> How to train models

but also:

> How to think like biomedical AI researchers and healthcare innovators.

The future belongs to those who can connect:

```text
Biology
   +
Data
   +
AI
   =
Health Intelligence
```

---

# 👨‍🏫 Lecturer

## 🎓 Teerapong Panboonyuen, Ph.D. (P'Kao)

Research Interests:

- Medical AI
- Bioinformatics
- Computer Vision
- Explainable AI
- Precision Medicine
- Machine Learning Systems

📫 Contact

```text
teerapong [dot] pa [at] chula [dot] ac [dot] th
```

---

# 🙏 Acknowledgements

Special thanks to:

- Big Data Institute (BDI)
- Khon Kaen University
- UCI Machine Learning Repository
- Kaggle Community
- Scikit-Learn Contributors
- XGBoost Developers
- SHAP Community
- Open-Source Scientific Ecosystem

and most importantly,

### 🌟 All BDI Young Innovators

who will shape the future of AI-driven healthcare.

---

# 📚 Citation

```bibtex
@misc{panboonyuen2026bdikku,
  title = {From Genomics to Phenomics: Machine Learning Foundations for Precision Medicine}
  author       = {Teerapong Panboonyuen},
  year         = {2026},
  howpublished = {\url{https://github.com/kaopanboonyuen/BDIKKU}},
  note         = {BDI Young Innovator Hackathon Workshop on Genomics, Phenomics and Healthcare AI}
}
```

---

<div align="center">

# 🧬 The Future of Medicine is Data-Driven

### DNA • Phenome • AI • Health Intelligence

🚀 Build AI That Improves Human Health

⭐ If this workshop inspires you, consider starring the repository.

</div>