# pymaitre
This organization is ment to have private tools for research aimed to help medical physicist in delivering tools for clinical usage. 
It is like a Maitre, not visible but present needed for an efficient and agile interaction with clinics. The idea behind is that we can have different maitres, 
with different tecnical profiles and from different institutes helping each other for the same scope.
Link to repositories are public documentation of them, the code is instead private.

A. Private libraries implemented for images (e.g., CT):
  1) **[dcm_folder](https://pymaitre.github.io/dcm_folder)**:
  Python library for DICOM folder organization.
  2) **[dcm_anonymize](https://pymaitre.github.io/dcm_anonymize)**:
  Code to anonimize dicom files in parallel.
  3) **[srmip](https://pymaitre.github.io/srmip)**:
  Python library for Medical Image Processing (MIP).
  4) **[libsrdl](https://pymaitre.github.io/libsrdl)**:
  Package for DL librabry applied to medical physics, applications for segmentation.

B. Private libraries implemented for databases:
  1) **[SQLHub](https://pymaitre.github.io/SQLHub)**:
  Code dealing with the interaction between analysis in Python and databases stored in SQL servers.
  2) **DBpromod**:
  Python library for database preprocessing.
  3) **DBanalysis**:
  Python library for AI models, optimization and boostrapping tecniques.
  4) **DBoutputs**:
  Python library for saving plots and Excel databases.
  5) **medicalAI**:
  It uses the cited in-house DB codes (B: 1, 2, 3, 4) to preprocess data, select best features (e.g. bootstrap or backward feature selection), 
  run models (logit and more complex AI models), extract plots (e.g., ROC, PR, calibration map) and perform prediction on new data.

REFERENCE PAPERS:
- [Ubeira-Gabellini et al. 2024](https://doi.org/10.3390/cancers16050934) (Cancers 2024, 16(5), 934, doi: https://doi.org/10.3390/cancers16050934) using medicalAI
- Pavarini et al. 2024 (in prep.) using medicalAI

NOTES:
The documentation is under construction.
