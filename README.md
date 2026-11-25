# Analysis codes of "Ocean oxygenation during the Last Interglacial from a multi-model perspective"
This repository contains the analysis codes used to generate all figures and tables presented in the manuscript "Ocean Oxygenation During the Last Interglacial from a Multi-Model Perspective", including those presented in the Appendix.

## Datasets
This study uses outputs from seven climate and ocean models: HadCM3, KCM, ACCESS-ESM1.5, IPSL-CM6A-LR, MIROC-ES2L, NorESM1-F and NorESM2-LM. The datasets used in this study were obtained from the following sources:
- HadCM3 and KCM: Model outputs for oxygen (O₂), Apparent Oxygen Utilisation (AOU), and oxygen saturation (O₂SAT), in the form of climatologies and anomalies, can be downloaded from Zenodo: https://doi.org/10.5281/zenodo.24297316
- ACCESS-ESM1.5: Model outputs are available from the University of New South Wales repository: https://doi.org/10.26190/unsworks/30420 (Yeung, 2024).
- IPSL-CM6A-LR, MIROC-ES2L, NorESM1-F and NorESM2-LM: Model outputs were obtained from the Earth System Grid Federation (ESGF): https://esgf-node.ornl.gov/ (last accessed on 8 September 2026).
## Requirements to run these codes
- Python v3.5.2 (as minimum) https://www.python.org/downloads/
- Jupyter notebook web interface https://jupyter.org/
- Python libraries. The most recurrent used here are NumPy, Matplotlib, Iris and Cartopy.
## List of jupyter notebooks
The Jupyter notebooks are organised into three folders according to the main variables and analyses presented in the manuscript: O₂, O₂SAT and AOU.
1) O₂
This folder contains two notebooks, as follows:
- Oxygen analyses: Generates the oxygen analysis figures (Figures 1, A1, 2 and A2 in the manuscript).
- O₂SAT and AOU contributions: Analyses the relative contributions of O₂SAT and AOU to the LIG–PI oxygen anomalies (Figures A7–A9 in the manuscript).
2) O₂SAT
This folder contains three notebooks, as follows:
- O₂SAT anomalies: Generates the oxygen saturation anomaly figures (Figures 3 and A3 in the manuscript).
- Potential temperature: Generates the potential temperature figures (Figures 4 and A4 in the manuscript).
- MOW: Analyses the variables associated with MOW (Figure A5 in the manuscript).
3) AOU
This folder contains nine notebooks, as follows:
- AOU anomalies: Generates the AOU anomaly figures (Figures 5 and A6 in the manuscript).
- Meridional overturning circulation: Analyses the meridional overturning circulation (Figures A10–A12 in the manuscript).
- Seawater anomalies by basin: Examines seawater anomalies across different ocean basins (Figures 6 and A13 in the manuscript).
- Mixed layer depth (MLD), AOU and seawater age: Investigates MLD in relation to AOU and seawater age (Figures 7 and A14 in the manuscript).
- Zonal mean wind stress: Analyses zonal mean wind stress (Figures 8 and A15 in the manuscript).
- Arabian Sea seawater anomalies: Examines seawater anomalies in the Arabian Sea (Figure 9 in the manuscript).
- Export production anomalies: Analyses export production anomalies (Figures 10 and A16 in the manuscript).
- North Pacific wind stress anomalies: Examines wind stress anomalies in the North Pacific (Figure 11 in the manuscript).
- Nitrate (NO₃) anomalies: Analyses nitrate anomalies (Figures 12 and A17 in the manuscript).



All codes finalised on 17/11/2026
Codes developed by Katya Canal-Solis (katyacanal@gmail.com)
