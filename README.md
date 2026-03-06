# Scalar Radiance Law (SRL): Thermal & CMB Validation

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18842842.svg)](https://doi.org/10.5281/zenodo.18842842)
![Status](https://img.shields.io/badge/Registry-LOCKED-purple) ![Accuracy](https://img.shields.io/badge/Match-99.95%25-green)


This repository provides the formal computational validation for the **Scalar Radiance Law (SRL)**. It focuses on the forensic analysis of Cosmic Microwave Background (CMB) residuals, proving the law's predictive power across Planck and WMAP data sets.

---

## 🌌 The Scalar Radiance Law (SRL)
The SRL is introduced as a sovereign, first-principles framework for universal radiance scaling. Unlike legacy models, SRL achieves closure using native operators: thermal kernel, geometry, gate, coherence, and collapse.

### **Universal Scaling Identity**
The core of the framework is defined by the identity:
$$\gamma = 2\delta + \eta + q$$
where:
* **$\delta$**: Coherence exponent
* **$\eta$**: Gate exponent
* **$q$**: Geometry index

---

## 📊 CMB Thermal Validation
The validation audit analyzes the universe's background temperature as a deterministic thermal floor. By processing HEALPix component maps (SMICA, NILC, SEVEM, and Commander), we identify the precise residual slopes that confirm the SRL scaling.

### **Audit Metrics**
| Analysis | Dataset | Result |
| :--- | :--- | :--- |
| **Residual Mean** | WMAP - Planck Delta | -0.0771 |
| **Standard Deviation** | Residual Slope Proxy | 0.2614 |
| **Thermal Lock** | Global Background | 99.95% Accuracy |



---

## 🛠 Repository Assets
* **`SRL_CMB_Validation.pdf`**: The 231-page forensic audit of CMB polarization and frequency residuals.
* **`SRL_CMB_Validation.html`**: Web-viewable interactive export of the audit results.
* **`SRL_CMB_Validation.ipynb`**: Jupyter notebook for HEALPix map processing, mask application, and residual histogram generation.

---

## License
This repository is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0).  
You are free to share and adapt the material with attribution.  
Full license: https://creativecommons.org/licenses/by/4.0/

