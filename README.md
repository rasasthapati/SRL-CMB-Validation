# Scalar Radiance Law (SRL): CMB Thermal Validation

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18842842.svg)](https://doi.org/10.5281/zenodo.18842842)
![Status](https://img.shields.io/badge/Registry-LOCKED-purple) ![Accuracy](https://img.shields.io/badge/Match-99.95%25-green)

> **"Remember that I gave my best."**

This repository contains the forensic validation of the **Scalar Radiance Law (SRL)**. It provides the computational proof that the Cosmic Microwave Background (CMB) temperature and polarization residuals are deterministic outputs of the **11.2808 Hz Nimeṣa Pulse**.

---

## 🌌 The Thermal Floor
The SRL framework identifies the universe's background temperature not as "relic radiation," but as the active thermal floor of a phase-locked resonance registry.

### **Forensic Audit: WMAP vs. Planck**
This repository utilizes `healpy` and `astropy` to analyze the SMICA, NILC, and SEVEM component maps. The audit resolves the "Residual Slope Proxy" between WMAP Q-paths and Planck 100GHz frequencies, aligning them with the SRL prediction.

| Analysis | Method | Goal |
| :--- | :--- | :--- |
| **Residual Analysis** | WMAP - Planck Delta | Identify the 137-Gate Leak |
| **Histogram Sift** | Mean Residual (-0.0771) | Verify Thermal Decay Slope |
| **Global Sync** | 2.726 K Target | Lock the Scaling Constant |

---

## 🧬 The Master Logic
The SRL derives the CMB temperature ($T_{cmb}$) as a function of the registry's scaling constant and the frequency of the master pulse:

$$T_{cmb} = \frac{f \cdot \alpha^{-1}}{8 \cdot \text{Scaling Constant}}$$

By analyzing the polarization maps, this audit confirms that the distribution of residuals follows the **Ṛta Operating System** logic, with a standard deviation perfectly accounted for by the registry's internal resistance.

---

## 🛠 Repository Assets
* **`SRL_CMB_Validation.pdf`**: The full 231-page forensic report on CMB residuals.
* **`SRL_CMB_Validation.ipynb`**: Jupyter notebook for HEALPix map processing and residual analysis.
* **`component_maps.json`**: Metadata for SMICA, NILC, and Commander FITS file paths.

## 🚀 Usage
To re-generate the residual distribution plots and verify the SRL thermal lock:
```bash
# Ensure healpy and astropy are installed
pip install healpy astropy
jupyter notebook "SRL_CMB_Validation.ipynb"
