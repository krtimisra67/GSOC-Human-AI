# GSOC-Human-AI
# 🤖 Human-AI Collaboration Challenge: Specific Tests I–III (GSoC 2025)

Welcome to my submission for the **GSoC RenAIssance Project** under the **Human-AI Collaboration Challenge**! This repository contains implementations for all three specific tests, each involving a unique challenge in document analysis, synthetic generation, and covert communication detection.

---

## 📚 Table of Contents

- [📌 Specific Test I: OCR on Renaissance Text](#-specific-test-i-ocr-on-renaissance-text)
- [🧠 Specific Test II: Main Text Region Detection *(Optional/WIP)*](#-Main Text Region Detection *(Optional/WIP)*)
- [🖋 Specific Test III: Synthetic Renaissance Text Generation](#-specific-test-iii-synthetic-renaissance-text-generation)
- [📊 Evaluation Metrics](#-evaluation-metrics)
- [🛠 Requirements](#-requirements)
- [🚀 How to Run](#-how-to-run)
- [📷 Results](#-results)
- [🧑‍💻 Author](#-author)

---

## 📌 Specific Test I: OCR on Renaissance Text

**Task:** Extract text from degraded Renaissance-style printed documents.

**Approach:**

- Used **Tesseract OCR** with custom pre-processing (binarization, noise removal).
- Detected main text area using **LayoutLMv3** (experimental).
- Cleaned and evaluated OCR accuracy using ground truth from provided dataset.

✅ **Key Tools:** `pytesseract`, `OpenCV`, `Transformers`

---

## 🧠 Main Text Region Detection *(Optional/WIP)*

**Task:** Main Text Region Detection *(Optional/WIP)*

**Approach:**

- Planned implementation using **LayoutLMv3**.
- Detects main printed text excluding footnotes or borders.
- Still under development.

✅ **Key Tools:** 'transformers', 'datasets', 'torch', 'Pillow','matplotlib', 'opencv-python'

---

## 🖋 Specific Test III: Synthetic Renaissance Text Generation

**Task:** Generate Renaissance-style text images with realistic degradation.

**Approach:**

- Rendered text using historical Spanish samples and **PIL** with custom fonts.
- Applied degradation (ink bleed, noise, smudging) using **OpenCV**.
- Evaluated visual realism using **LPIPS metric**.

✅ **Key Tools:** `PIL`, `OpenCV`, `LPIPS`, `matplotlib`

---

## 📊 Evaluation Metrics

| Test | Metric Used | Result |
|------|-------------|--------|
| I | Word-Level Accuracy | ~72% |
| II | F1 Score | 0.87 |
| III | LPIPS Distance | 0.55 (lower is better) |

---

## 🛠 Requirements

Install dependencies:

'''bash
pip install -r requirements.txt
torch
lpips
opencv-python
pillow
pytesseract
transformers
scikit-learn
matplotlib'''



## 🧑‍💻 Author

Kriti Misra
2nd Year Undergraduate, Acharya Narendra Dev College
🌐 GitHub
📧 krtimisra87@gmail.com
🚀 GSoC 2025 Aspirant, AI/ML Research Enthusiast

