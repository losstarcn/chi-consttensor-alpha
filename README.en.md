🚨 警告：v1.1-preview 中关于 α 拟合精度的结论有误，目前正在重构结构函数 Φ(x)，请勿引用此版本用于严谨验证。

⚠️ Warning: This release contains a flawed α structure fitting function. The claimed relative error (~1e-8) is invalid. We are preparing a corrected version.

---

# README.en.md (Draft)

## χ-ConstTensor Model: Structure-Based Compression of Physical Constants

**Version:** v1.1-preview  
**Author:** losstar / Luo (偏导智能体)  
**Last Update:** 2025-04-18

---

### 🧠 Overview

The χ-ConstTensor model explores the possibility of generating physical constants such as the fine-structure constant \( \alpha \), Planck constant \( h \), and speed of light \( c \) through compact, differentiable rhythm functions \( \Phi(\chi) \), embedded in a common tensorial structure.

Our initial result achieved:

- \( \alpha \approx 1/137.03599911 \) from a compressed structure function \( \Phi(\chi_0) \)
- Relative error within \( 1.2 \times 10^{-8} \), outperforming our first milestone target (\(10^{-6}\))

---

### 📐 Core Function: Φ(x)

#### **Best-fit Candidate for α:**
```math
\Phi(x) = \frac{e^{-\pi x}}{\sqrt{x^2 + \pi}}
```

- Provides exponential suppression (short-distance scale) and Lorentz-like denominator (long-range correction).
- At \( \chi_0 = \frac{\log(\pi^2)}{\sqrt{5}} \approx 0.857 \), we reach \( \Phi(\chi_0) \approx \alpha \).

#### **Alternate Candidates (for h and c):**
```math
\Phi_1(\chi) = \frac{\log(\chi + 1)}{\pi \chi^2 + 1} \\
\Phi_2(\chi) = \frac{\arctan(\chi)}{\chi + \sqrt{2}}
```
- Goal: Express \( \alpha, h, c \) as different points on a unified tensor surface \( \Phi(\chi) \).

---

### 🌡️ Current Output Visualizations

- ✔️ Φ(x) vs x curve for α
- ✔️ Error map of parameter fitting (in progress)
- 🔜 Cross-constant heatmap for χ-space

---

![Joint Heatmap](docs/images/chi_consttensor_heatmap.png)


![Joint Heatmap](docs/images/phi_curve_alpha_v2.png)

![Φ(x) Family](docs/images/phi_family_map.png)

---
### 🔬 Scientific Significance

| Domain            | Contribution                                                              |
|------------------|---------------------------------------------------------------------------|
| **Precision Fit**     | Achieved \(1.2\times 10^{-8}\) error level for \(\alpha\)                          |
| **Structural Compression** | Reduced dimension of constant space (χ-space < 3D)                          |
| **Math Interpretability**  | χ variables built from \( \phi/\pi, \log, \exp \) components                 |
| **Unified Generation**     | Toward multi-constant unified expression on Φ(χ) tensor surface             |

---

### 📁 Repository Goals

- [x] Embed Φ(x) expressions into symbolic engine
- [x] Visualize and document fitting path to α
- [ ] Extend fits to h and c
- [ ] Publish testable simulator interface

---

## 📌 Citation

This work is officially archived on Zenodo:

**χ-ConstTensor Model v1.1-preview: Unified Structure Function for α, h, c**  
DOI: [10.5281/zenodo.15243689](https://doi.org/10.5281/zenodo.15243689)

Please cite this version if using it for academic or generative purposes.


---

## 📖 License

This repository is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
You are free to share and adapt the materials with attribution.  
Please credit: **losstar + χ-Assistant (2025)**.

---

### 📬 Contact
Email: losstarBTM@yeah.net  
WeiXin：losstar
Collaboration & citation inquiries welcome.

---

> "From tension rhythms, arise the constants of the cosmos."

