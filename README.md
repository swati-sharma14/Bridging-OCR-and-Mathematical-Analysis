# Bridging OCR and Mathematical Analysis

This repository contains the data and notebooks for **“Bridging OCR and Mathematical Analysis”**, a prototype pipeline that takes scanned mathematical answer sheets, extracts content with OCR, and then performs structured analysis of the solutions.

The goal is to go beyond plain text recognition and move toward **step-wise evaluation and feedback** for handwritten math solutions.

---

## 🚀 Project Overview

Traditional OCR systems are good at reading text, but they struggle when:

- Expressions are **handwritten** and noisy,  
- Layout is **2D** (fractions, matrices, subscripts/superscripts),  
- We care about **mathematical correctness**, not just transcription.

This project explores a workflow that:

1. **Ingests scanned answer sheets** from the provided dataset.
2. **Applies OCR** to extract mathematical content.
3. **Normalizes and parses expressions** into a structured representation.
4. **Compares predicted expressions/answers** against ground truth.
5. Provides basic **analysis and visualizations** of system performance.

---

## 📂 Repository Structure

```text
Bridging-OCR-and-Mathematical-Analysis/
├── Dataset/                   # Dataset used in the project (scans / related resources)
├── Answer Sheet - Sheet1.csv  # Ground truth / annotations for answer sheets
├── math_vista.ipynb           # Main notebook: OCR + math analysis experiments
├── naming.ipynb               # Helper notebook: dataset organisation / naming utilities
├── Technical_Report.pdf       # Technical report describing the project
└── README.md                  
