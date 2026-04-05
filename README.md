CCD Imaging and Photometric Analysis of M1
Overview

This project analyzes CCD imaging and photometric data to study image calibration, multi-filter imaging, and exoplanet transit behavior. By applying standard reduction techniques and photometric analysis, the dataset is used to examine both the structure of an astronomical object and variations in stellar brightness over time.

Why This Matters

CCD imaging is fundamental to modern observational astronomy. Accurate calibration is required to remove instrumental effects and recover true astrophysical signals. Multi-filter imaging provides information across different wavelengths, while photometric measurements allow detection and characterization of phenomena such as exoplanet transits.

Methods

Loaded CCD images in multiple filters (B, V, r)
Applied bias subtraction, dark correction, and flat-fielding
Constructed reduced images for each filter
Combined images into an RGB composite
Used photometric measurements to calculate relative flux
Generated a light curve from time-series data
Identified a transit event in the light curve
Modeled the transit using a box-shaped function
Estimated transit depth, duration, and signal-to-noise

Results
Image Calibration

The reduction process removes background artifacts and corrects for instrumental effects, producing cleaner and more uniform images.

Multi-Filter Imaging

The RGB composite reveals structure across wavelengths, highlighting differences captured by each filter.

Light Curve Analysis

The light curve shows a clear decrease in flux during the transit event, indicating a measurable change in brightness over time.

Transit Properties

Estimated transit depth: ~0.005–0.006 (normalized flux)
Estimated transit duration: ~4 hours
Signal-to-noise ratio indicates a detectable transit signal

The results show consistent image calibration and a clear photometric signal, demonstrating the ability to extract physical information from observational data.

Important Note on Analysis

The transit model used is a simplified box approximation. While effective for estimating depth and duration, it does not capture detailed physical effects such as limb darkening or full orbital geometry.

Visualizations
Raw vs Calibrated Images

Calibration Comparison

RGB Composite Image

RGB Composite

Light Curve

Light Curve Plot

Transit Model Fit

Transit Fit

How to Run

Clone the repository

Install required libraries:

NumPy
Pandas
Matplotlib
Astropy

Ensure all FITS images and photometry files are in the project directory

Run:

jupyter notebook observational-astrophysics-analysis-CCD.ipynb

Tools Used

Python
NumPy
Pandas
Matplotlib
Astropy
DS9
AstroImageJ

Future Improvements

Implement a physically motivated transit model
Perform full uncertainty propagation
Incorporate atmospheric extinction corrections
Analyze multi-filter data quantitatively
Extend analysis to additional datasets

Author

Danessa Ruff

Michigan State University
