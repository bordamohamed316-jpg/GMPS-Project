# Probing Ultra-Light Scalar Condensate Dark Matter with the Nancy Grace Roman Space Telescope

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23965322.svg)](https://doi.org/10.5281/zenodo.23965322)

This repository provides the numerical simulation pipeline, cosmological perturbation routines, and Fisher matrix forecasting tools for the research paper:

> **"Probing Ultra-Light Scalar Condensate Dark Matter with the Nancy Grace Roman Space Telescope: Complete Linear Perturbation Theory and Cosmic Shear Forecasts"**  
> *Author: Mohamed Abdelmomen Abu Borda*  
> *Permanent Archive:* [Zenodo (DOI: 10.5281/zenodo.23965322)](https://doi.org/10.5281/zenodo.23965322)

---

## 🔬 Scientific Summary

Standard Cold Dark Matter ($\Lambda$CDM) faces persistent sub-galactic challenges (the core-cusp problem, missing satellites, and the $S_8$ tension). This research derives a closed linear perturbation formulation for an **ultra-light scalar condensate dark matter model** characterized by:
$$m_\phi \approx 2.2 \times 10^{-22}\text{ eV}$$

### Key Findings
1. **Quantum Hydrodynamics:** Starting from the field action, we derive the exact Bohm quantum potential and stress tensor via the Madelung transformation in expanding FLRW spacetime.
2. **Acoustic Jeans Cutoff:** Gravitational instability is arrested below the de Broglie wavelength, yielding an exact half-mode cutoff at:
   $$k_{1/2} = 10.19 \, h\,\text{Mpc}^{-1}$$
3. **Roman Space Telescope Forecast:** Projected onto the 2D cosmic shear convergence power spectrum ($C_\ell^{\kappa\kappa}$) for the High Latitude Wide Area Survey (HLWAS), predicting an $8\% - 15\%$ deficit at multipoles $\ell \in [3000, 5000]$.
4. **Cumulative Detection Significance:**
   $$\mathbf{S/N = 5.38\sigma}$$
   exceeding the standard $5\sigma$ discovery threshold.

---

## 📁 Repository Files

* `roman_shear_forecast.py`: The complete numerical code computing $C_\ell$ spectra, multipole binning, and Fisher SNR.
* `roman_shear_forecast.pdf`: High-resolution vector plot showing the Roman forecast against $\Lambda$CDM.

---

## 🚀 Execution

To reproduce the analysis locally or on Google Colab:
```bash
python roman_shear_forecast.py
@article{AbuBorda2026Roman,
  author        = {Mohamed Abdelmomen Abu Borda},
  title         = {{Probing Ultra-Light Scalar Condensate Dark Matter with the Nancy Grace Roman Space Telescope: Complete Linear Perturbation Theory and Cosmic Shear Forecasts}},
  year          = {2026},
  doi           = {10.5281/zenodo.23965322},
  howpublished  = {\url{https://github.com/bordamohamed316-jpg/GMPS-Project}}
}
📬 Contact

Mohamed Abdelmomen Abu Borda
Independent Theoretical Physics Researcher, Cairo, Egypt
Email: bordamohamed316@gmail.com
