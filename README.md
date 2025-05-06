# 🧬 CAR-T_QSP_Resistance_Model

This project integrates **single-cell RNA sequencing (scRNA-seq)** data and **quantitative systems pharmacology (QSP)** modeling to investigate **CAR-T cell resistance** mechanisms in **multiple myeloma**. It simulates treatment kinetics, tumor clearance, CAR-T expansion, and exhaustion using **MATLAB SimBiology**, supported by transcriptional data from pre- and post-treatment patient samples.

---

## 🔬 Objective

- Model CAR-T therapy in multiple myeloma with a focus on early relapse and T cell exhaustion.
- Integrate scRNA-seq insights (T cell decline, BCMA+ tumor evolution).
- Perform sensitivity analysis to identify key pharmacodynamic drivers (e.g., `k_kill`, `k_exhaustion`).

---

## 🧪 Tools & Data

| Category | Tools |
|----------|-------|
| Systems Modeling | MATLAB SimBiology |
| Transcriptomics | Seurat (R), UMAP |
| Source Data | Lee et al., *Nat Med* (2023) |
| Analysis | Sensitivity analysis, AUC calculations, parameter fitting |

---

## 📁 Project Structure

