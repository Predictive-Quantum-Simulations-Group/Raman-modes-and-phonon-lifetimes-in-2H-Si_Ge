**Raman Spectra Calculations for 2H Silicon and Germanium**

This repository contains input files, output data, and processed results for ab initio Raman spectroscopy calculations of hexagonal (2H) Silicon (Si) and Germanium (Ge).
The calculations are performed using density functional theory (DFT) using Quantum ESPRESSO and the QERaman package.

The workflow followed is:

1. Perform self-consistent field (SCF) calculation.
2. Usiing the QERaman package,  
 a. Compute the bands calculation using bands_mat.x utility to obtain the electron-photon matrix elements.  
 b. Compute phonon properties using ph_mat.x for the electron-phonon matrix elements  
 c. Evaluate Raman tensor using raman.x.  
3. Post-processing of the data to obtain the Raman spectra.

**References**

https://doi.org/10.1016/j.cpc.2023.108967  
https://doi.org/10.1088/0953-8984/21/39/395502
