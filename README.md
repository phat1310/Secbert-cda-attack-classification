# MITRE ATT&CK Technique Classification using SecBERT and Contextual Data Augmentation

> An academic research project on automated Cyber Threat Intelligence (CTI) analysis using domain-adapted language models for MITRE ATT&CK technique classification.

> **Project Status:** Active Research (Paper in Preparation)

---

## Overview

Cyber Threat Intelligence (CTI) reports contain valuable information describing adversarial behaviors, attack procedures, and defensive insights. However, these reports are primarily written in unstructured natural language, making large-scale analysis difficult.

This project investigates automatic mapping of CTI reports to MITRE ATT&CK techniques using domain-adapted transformer models. The research focuses on improving classification performance under severe class imbalance through Contextual Data Augmentation (CDA) while evaluating both single-label and multi-label learning scenarios.

The project is currently under active development as part of an academic research study.

---

## Research Objectives

The primary objectives of this project are:

- Develop an automated framework for MITRE ATT&CK technique classification.
- Evaluate SecBERT for cybersecurity-specific natural language understanding.
- Improve minority-class prediction using Contextual Data Augmentation.
- Compare single-label and multi-label classification strategies.
- Analyze model behavior through comprehensive error analysis.

---

## Research Highlights

- Domain-specific language model (SecBERT)
- Contextual Data Augmentation (CDA)
- Single-label classification (TRAM1)
- Multi-label classification (TRAM2)
- Long-tail class imbalance analysis
- Comprehensive experimental evaluation
- Error analysis for semantically similar ATT&CK techniques

---

## Repository Structure

```text
mitre-attack-secbert-cda/
│
├── paper/             Research manuscript (LaTeX)
├── datasets/          Dataset information
├── src/               Source code
├── notebooks/         Experimental notebooks
├── configs/           Training configurations
├── outputs/           Experimental results
├── figures/           Figures used in paper
├── docs/              Project documentation
├── scripts/           Utility scripts
└── README.md
```

---

## Current Progress

| Stage | Status |
|--------|--------|
| Literature Review | ✅ Completed |
| Dataset Analysis | ✅ Completed |
| Data Preprocessing | ✅ Completed |
| Baseline Models | ✅ Completed |
| SecBERT Fine-tuning | ✅ Completed |
| Contextual Data Augmentation | ✅ Completed |
| Experimental Evaluation | ✅ Completed |
| Error Analysis | ✅ Completed |
| Paper Writing | 🚧 In Progress |
| Code Refactoring | ⏳ Planned |
| Documentation | ⏳ Planned |
| Public Release | ⏳ Planned |

---

## Technology Stack

- Python
- PyTorch
- Hugging Face Transformers
- SecBERT
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

## Datasets

This project is evaluated using publicly available Cyber Threat Intelligence datasets.

| Dataset | Task |
|----------|------|
| TRAM1 | Single-label classification |
| TRAM2 | Multi-label classification |

Detailed dataset information and download instructions will be provided in the `datasets/` directory.

---

## Project Roadmap

### Phase 1 — Foundation

- Repository initialization
- Documentation
- Research organization

### Phase 2 — Code Release

- Source code
- Training pipeline
- Evaluation scripts

### Phase 3 — Dataset Documentation

- Dataset preparation
- Preprocessing pipeline
- Data statistics

### Phase 4 — Experiment Reproduction

- Training configuration
- Hyperparameters
- Result reproduction

### Phase 5 — Publication

- Camera-ready paper
- Citation
- DOI
- Release v1.0

---

## Repository Status

This repository is currently under active development.

The source code, documentation, and reproducibility pipeline will be released progressively as the research project advances.

---

## License

This repository will be released under the MIT License.

---

## Contact

**Tan Phat Nguyen**

Faculty of Information Assurance

FPT University

Email: *Coming Soon*

GitHub: https://github.com/phat1310
