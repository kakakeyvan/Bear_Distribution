# Persian Music Shour — Bear Distribution

Reproducibility repository for:

**The Bear Distribution: A Context-Adaptive Hierarchical Bayesian Model for Persian Classical Music**

*Keyvan Yahya, Mehdi Shams*

---

## Contents

- `Data sheets/` — Symbolic corpus of the Shour dastgah
- `notebooks/` — Jupyter notebook reproducing all results

---

## Quick Start

**1.** Upload `ShourCorpus-main.zip` to Google Colab (📁 icon → Upload).

**2.** Extract:

```python
import zipfile
with zipfile.ZipFile("/content/ShourCorpus-main.zip") as z:
    z.extractall("/content/ShourCorpus")


