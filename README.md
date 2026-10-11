# Persian Music Shour — Bear Distribution

Reproducibility repository for the manuscript:

**The Bear Distribution: A Context-Adaptive Hierarchical Bayesian Model for Persian Classical Music**

*Keyvan Yahya, Mehdi Shams*

---

## Overview

This repository contains the symbolic corpus and reproducibility code for the study of Persian classical music (Shour dastgah) using a hierarchical Bayesian framework termed the **Bear Distribution**.

The repository includes:

- **`Data sheets/`** — Symbolic corpus of the Shour dastgah (26 gushehs in CSV format)
- **`notebooks/`** — Jupyter notebook reproducing all results reported in the manuscript

---

## Quick Start

### Step 1 — Upload the corpus

Download `ShourCorpus-main.zip` and upload it to Google Colab:

- Click the folder icon (📁) in the left sidebar
- Click **Upload** and select `ShourCorpus-main.zip`
- Wait for the upload to complete

### Step 2 — Extract the corpus

Run this cell in Colab:

```python
import zipfile

with zipfile.ZipFile("/content/ShourCorpus-main.zip", "r") as z:
    z.extractall("/content/ShourCorpus")

print("Extraction complete.")


