# 🦷 RestorativeAI: A Multimodal AI System for Diagnostic Support in Dentistry

This repository contains the codebase and resources for the thesis project titled **"A Multimodal AI System for Diagnostic Support and Treatment Planning in Restorative Dentistry"**. The system combines radiographic imaging (OPGs, CTs) and clinical notes to build AI-driven diagnostic and planning tools.

---

## 🔍 Project Overview

- **Modality 1**: Panoramic X-rays (OPGs)
- **Modality 2**: Cone-beam CT Scans (CBCTs)
- **Modality 3**: Clinical Diagnosis & Metadata
- **Goal**: Segment dental structures, classify conditions (e.g., implant need, crown viability), and assist with treatment planning.

---

## 📁 Directory Structure

- `data/`: Raw and processed datasets (images, CTs, text)
- `notebooks/`: Prototyping and visualization in Jupyter
- `src/`: Core modules for modeling, data loading, evaluation
- `models/`: Checkpoints and architecture definitions
- `outputs/`: Logs, predictions, visualizations
- `tests/`: Unit and integration tests
- `scripts/`: Training and inference scripts
- `docs/`: Thesis documents and research papers
- `assets/`: Figures and images for documentation

---

## 🧪 Reproducibility

- Python ≥ 3.9
- PyTorch ≥ 2.0
- torchvision, scikit-learn, MONAI, transformers, OpenCV

Install via:
```bash
pip install -r requirements.txt
