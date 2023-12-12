# pymaitre
This organization is ment to have private tools for research aimed to help medical physicist in delivering tools for clinical usage. 
It is like a Maitre, not visible but present needed for an efficient and agile interaction with clinics. The idea behind is that we can have different maitres, 
with different tecnical profiles and from different institutes helping each other for the same scope.
Link to repositories are public documentation of them, the code is instead private.

Private libraries implemented for images (e.g., CT):
1) **[dcm_folder](https://pymaitre.github.io/dcm_folder)**:
Python library for DICOM folder organization.
2) **[dcm_anonymize](https://pymaitre.github.io/dcm_anonymize)**:
Code to anonimize dicom files in parallel.
3) **[srmip](https://pymaitre.github.io/srmip)**:
Python library for Medical Image Processing (MIP).
4) **[libsrdl](https://pymaitre.github.io/libsrdl)**:
Package for DL librabry applied to medical physics, applications for segmentation.

Private libraries implemented for databases:
5) **[SQLHub](https://pymaitre.github.io/SQLHub)**:
Code dealing with the interaction between analysis in Python and databases stored in SQL servers.
6) **DBpromod**:
Python library for database preprocessing.
7) **DBanalysis**:
Python library for AI models, optimization and boostrapping tecniques.
8) **DBoutputs**:
Python library for saving plots and Excel databases.
9) **medicalAI**:
It uses the cited in-house DB codes (5, 6, 7, 8) to preprocess data, select best features (e.g. bootstrap or backward feature selection), 
run models (logit and more complex AI models), extract plots (e.g., ROC, PR, calibration map) and perform prediction on new data.

REFERENCE PAPERS:
- Ubeira-Gabellini et al. 2024 (in prep.) using medicalAI
- Pavarini et al. 2024 (in prep.) using medicalAI
