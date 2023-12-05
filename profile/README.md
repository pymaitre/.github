# pymaitre
This organization is ment to have private tools for research aimed to help medical physicist in delivering tools for clinical usage. 
It is like a Maitre, not visible but present needed for an efficient and agile interaction with clinics. The idea behind is that we can have different maitres, 
with different tecnical profiles and from different institutes helping each other for the same scope.

Tools implemented for images (e.g., CT):
1) dcm_folder
Python library for DICOM folder organization.
2) dcm_anonymize
Code to anonimize dicom files in parallel.
3) srmip
Python library for Medical Image Processing (MIP).
4) libsrdl
Package for DL librabry applied to medical physics, applications for segmentation.

Tools implemented for databases:
a) SQLHub
Code dealing with the interaction between analysis in Python and databases stored in SQL servers.
b) DBpromod
Python library for database preprocessing.
c) DBanalysis
Python library for AI models, optimization and boostrapping tecniques.
d) DBoutputs
Python library for saving plots and Excel databases.
e) medicalAI
It uses the cited in-house DB codes to preprocess data, select best features (e.g. bootstrap or backward feature selection), 
run models (logit and more complex AI models), extract plots (e.g., ROC, PR, calibration map) and perform prediction on new data.
