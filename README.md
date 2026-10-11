# Persian Music Shour — Bear Distribution

Reproducibility repository for the manuscript:

**The Bear Distribution: A Context-Adaptive Hierarchical Bayesian Model for Persian Classical Music**
Keyvan Yahya, Mehdi Shams

## Overview

This repository contains the code and symbolic corpus used in the 
study of Persian classical music (Shour dastgah) with a hierarchical 
Bayesian framework termed the Bear Distribution.

## Contents

- `notebooks/` — Jupyter notebooks for all experiments
- `data/` — Symbolic corpus (Shour dastgah gushehs)
- `results/` — Output CSVs and figures
- `requirements.txt` — Python dependencies

## Notebooks

| Notebook | Description |
|---|---|
| `01_generation.ipynb` | Generate 1000 melodies per gusheh |
| `02_distributional_divergence.ipynb` | KL/JS/TV/Hellinger analysis |
| `03_nested_validation.ipynb` | 6-model comparison |
| `04_extended_corpus.ipynb` | Full-corpus analysis |

## Setup

```bash
pip install -r requirements.txt


