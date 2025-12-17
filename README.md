# Software Effort Estimation Benchmarking

This repository contains the implementation of a benchmarking framework for **software effort estimation** across **two data granularities**:
1. **Story Point–level estimation**
2. **Project-level estimation**

The benchmark evaluates and compares **traditional Machine Learning (ML)** models, **Transformer-based models**, and **Large Language Models (LLMs)** using textual and engineered software features (e.g., TF-IDF).

---

## 📊 Estimation Tasks

- **Story Point Estimation**  
  Predicting effort at the user story level based on textual descriptions and associated features.

- **Project-Level Estimation**  
  Predicting overall software project effort/cost using aggregated project information.

---

## 🧠 Model Categories

- **Machine Learning Models**  
  Classical regression-based approaches using engineered features.

- **Transformer-Based Models**  
  Deep contextual representations for software-related text.

- **Large Language Models (LLMs)**  
  Prompt-based estimation approaches in zero-shot or few-shot settings.

---

## 📁 Repository Structure

```
├── helper.py
├── prepareData.py
├── preprocessing.py
├── ml_for_story_point.py
├── ml_for_software_estimation.py
├── trans_based_for_story_point.py
├── trans_based_for_software_estimation.py
└── features/
    └── TF-IDF/
```

---

## ⚙️ Usage

1. **Data Preparation and Preprocessing**
   ```bash
   python prepareData.py
   ```

2. **Run ML-Based Models**
   ```bash
   python ml_for_story_point.py
   python ml_for_software_estimation.py
   ```

3. **Run Transformer-Based Models**
   ```bash
   python trans_based_for_story_point.py
   python trans_based_for_software_estimation.py
   ```

---

## 🎯 Research Goal

The goal of this repository is to provide a **reproducible and extensible benchmark** for analyzing how different modeling paradigms (ML, Transformer-based models, and LLMs) perform across **different software estimation levels** and **data representations**.

This codebase is intended to support empirical research and comparative studies in software effort estimation.

---

## 📖 Citation

If you use this code in your research, please cite the following paper:

```bibtex
@article{Alaswad2025SoftwareEstimation,
  title   = {Benchmarking Machine Learning, Transformer-Based, and Large Language Models for Software Effort Estimation},
  author  = {Alaswad, Feisal and Aljaddouh, Batoul and Poovammal, E.},
  journal = {Under Review},
  year    = {2025}
}
```

(Please update the publication venue and year once finalized.)

---

## 📄 License

Add your license information here (e.g., MIT License).
