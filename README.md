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

**d3q Workflow for Third-Order Anharmonic Calculations**

The workflow for computing third-order interatomic force constants (IFCs) using Density Functional Perturbation Theory (DFPT) as implemented in Quantum ESPRESSO and d3q package is given as follows.  

The calculation proceeds in the following stages:

1. Ground-state (SCF) calculation
2. Phonon calculation on a q-point grid (ph.x)
3. Third-order perturbation calculation (d3q.x)
4. Post-processing for real-space IFCs and transport properties

**References**

https://doi.org/10.1016/j.cpc.2023.108967  
https://doi.org/10.1088/0953-8984/21/39/395502  
https://doi.org/10.1103/PhysRevB.87.214303
