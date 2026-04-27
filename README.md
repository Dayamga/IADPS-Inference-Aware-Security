# IADPS-Inference-Aware-Security

Inference-Aware Data Protection System (IADPS): A hybrid CRF + HGB framework for detecting and mitigating inference attacks in Biba-based enterprise security architectures, with cumulative leakage modeling and relevance-aware control.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19759480.svg)](https://doi.org/10.5281/zenodo.19759480)

---

## 📌 Overview

This repository contains the implementation of the **Inference-Aware Data Protection System (IADPS)**, a framework designed to detect, monitor, and mitigate inference-driven information leakage in enterprise security systems.

While traditional access control models (e.g., Biba) enforce *access correctness*, they do not prevent **inference attacks** arising from correlated or sequential queries. IADPS addresses this limitation by introducing **relevance-aware inference control and bounded leakage enforcement**.

---

## 🔬 Key Contributions

- 📊 **Cumulative inference leakage model**
  \[
  \mathcal{L}_n = \sum_{i=1}^{n} \mathrm{Rel}(X_i;Y)
  \]

- 🤖 **Hybrid Machine Learning Framework**
  - Conditional Random Fields (CRF)
  - HistGradientBoosting (HGB)
  - CRF-probability integration

- 🔍 **Inference-aware query validation (SQVS)**
- 🔐 **Differential Privacy integration**
- ⚙️ **Software and Hardware deployment models**
- 🛡️ **Fallback guarantees for bounded inference leakage**

---

## 🏗️ Architecture

> *(Add your architecture image here once uploaded)*

```markdown
![IADPS Architecture](figures/iadps_architecture.png)
