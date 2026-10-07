# Bear_Distribution
Bayesian Modelling of the Persian Dastgah Shur
# Bayesian / Bear Distribution — Publication Figures

Publication-quality figures for the **Journal of New Music Research** manuscript on the *Bear Distribution* (Bayesian) model for Persian classical music (radif) prediction across gushehs.

---

## 📖 Overview

This script generates four publication-ready figures (PDF + PNG, 300 DPI) summarizing the predictive performance of four models:

| Model | Description |
|---|---|
| **Empirical** | Baseline empirical distribution over the training corpus |
| **BearV1** | Bayesian Bear Distribution (v1) |
| **Interpolated 2-gram** | Linear interpolation of bigram statistics |
| **Hierarchical 3-gram** | Hierarchical trigram model |

Evaluation is performed over **50 structural cross-validation splits**, with **95% confidence intervals** computed via the Student's *t*-distribution (`t(49) = 2.0096`).

---

## 📊 Generated Figures

| Figure | Filename | Description |
|---|---|---|
| **Figure 1** | `Figure_1_Overall_Performance_95CI.{pdf,png}` | Overall mean **Log Loss** (a) and **Perplexity** (b) with 95% CIs |
| **Figure 2** | `Figure_2_Gusheh_LogLoss_Heatmap.{pdf,png}` | Heatmap of mean Log Loss across 10 gushehs × 4 models |
| **Figure 3** | `Figure_3_JS_Divergence.{pdf,png}` | Jensen–Shannon divergence between predicted and empirical distributions per gusheh |
| **Figure 4** | `Figure_4_Paired_LogLoss_Comparisons.{pdf,png}` | Paired Log Loss differences between model pairs with 95% CIs |

All figures are exported in **both PDF (vector)** and **PNG (raster, 300 DPI)** formats.

---


