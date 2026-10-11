# Persian Music Shour — Bear Distribution

Reproducibility repository for the manuscript:

**The Bear Distribution: A Context-Adaptive Hierarchical Bayesian Model for Persian Classical Music**
Keyvan Yahya, Mehdi Shams

## Overview

This repository contains the code and symbolic corpus used in the 
study of Persian classical music (Shour dastgah) with a hierarchical 
Bayesian framework termed the Bear Distribution.
## How to Run This Notebook

This notebook reproduces all results reported in the manuscript. Follow 
the steps below carefully.

### Step 1 — Upload the Corpus

The symbolic corpus is distributed as a ZIP archive (`ShourCorpus-main.zip`). 
You need to upload it to the Colab environment before running any code.

**Option A — Upload via the Files panel (recommended for mobile):**

1. Click the folder icon (📁) in the left sidebar of Google Colab.
2. Click the **Upload** button (📤).
3. Select `ShourCorpus-main.zip` from your device.
4. Wait for the upload to complete (a progress bar will appear).

**Option B — Upload via code:**

```python
from google.colab import files
uploaded = files.upload()
# Select ShourCorpus-main.zip when prompted

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


