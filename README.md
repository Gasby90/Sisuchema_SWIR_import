# Sisuchema_SWIR_import
The 'Sisuchema_SWIR_import.m' allows to import raw and calibration data acquired by SisuChema XL Spectrophotometer into MATLAB and calculates the effective reflectance data cube. 
The following is the procedure to follow when running “Sisuchema_SWIR_import.m”:
1.	Open .hdr raw data,
2.	Open .hdr dark reference,
3.	Open .hdr white.
The script operates bicubic interpolation smoothing on dark and white reference and then calculates the “REFL” dataset containing the reflectance values obtained. 

'Sisuchema_SWIR_import.m' script was thought for working with MATLAB® 2016a ver. 9.0 alongside PLS_toolbox ver. 8.2.
Please note: it may requires a lot of RAM!

[![DOI](https://zenodo.org/badge/274688908.svg)](https://zenodo.org/badge/latestdoi/274688908)
