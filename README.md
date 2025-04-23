# AUTOWADE2.0 Pseudocode

This repository provides the complete, structured pseudocode of the **AUTOWADE2.0** algorithm, designed for flood mapping using Synthetic Aperture Radar (SAR) data. The pseudocode reflects the operational logic and implementation strategy used in the research described in our manuscript submitted to the *ISPRS Journal of Photogrammetry and Remote Sensing*.

## 📄 Contents

- `AUTOWADE2.0_Pseudocode_Final_Clean_Complete.docx`: Full IDL-style pseudocode
- *(Optional)* `AUTOWADE2.0_Pseudocode_Final_Clean_Complete.pdf`: Printable version for citation and archival

## 🧠 Purpose

Due to licensing constraints with IDL and the proprietary nature of some input data, the full implementation code cannot be shared. Instead, this pseudocode offers a complete and detailed representation of the AUTOWADE2.0 logic for:

- Benchmarking against other flood detection algorithms
- Ensuring reproducibility of research
- Supporting integration with alternate languages or platforms

## 📚 Reference

Please cite the following article if you use this pseudocode or reproduce parts of the algorithm:

> Pulvirenti, L., et al. (2025). Continuous flood monitoring using on-demand SAR data acquired with different geometries: methodology and test on COSMO-SkyMed images. ISPRS Journal of Photogrammetry and Remote Sensing. [DOI]

## 🛠️ Algorithm Overview

AUTOWADE2.0 includes:

- Cross-normalization of pre- and post-event SAR images
- Unsupervised ISODATA clustering
- Electromagnetic model-based thresholding
- Pixel-level fuzzy logic integration
- Seed-based region growing constrained by SAR intensity and shape
- Final product filtering and export

## 🔍 Notes

- The pseudocode follows IDL (Interactive Data Language) structure and logic.
- Raster operations assume the use of ENVI software for geospatial processing.
- Fuzzy logic parameters are derived from modeled backscatter thresholds and object area distributions.

## 📝 License

This repository is distributed for academic, research, and non-commercial use only.

---

For questions or collaborations, please contact:  
[Luca Pulvirenti](mailto:luca.pulvirenti@cimafoundation.org)  
CIMA Research Foundation, Italy
