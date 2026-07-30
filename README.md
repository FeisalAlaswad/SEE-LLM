# Software Effort Estimation Benchmarking

This repository contains the implementation of a benchmarking framework for **software effort estimation** across **two data granularities**:
1. **Story Point–level estimation**
2. **Project-level estimation**

The benchmark evaluates and compares **traditional Machine Learning (ML)** models, **Transformer-based models**, and **Large Language Models (LLMs)** using textual and engineered software features (e.g., TF-IDF).

---

## 📖 Citation

If you use this code in your research, please cite the following paper (not yet published):
(Should be updated)
```bibtex
@article{alaswad2026cocomo,
  title={From cocomo to gpt: A comprehensive evaluation of llm-based software effort estimation},
  author={Alaswad, Feisal and Poovammal, E and Aljaddouh, Batoul},
  journal={IEEE Access},
  year={2026},
  publisher={IEEE}
}
```



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



## 📄 License

MIT License

Copyright (c) 2025 Feisal Alaswad

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
