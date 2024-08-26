# Exposure Time Calculator

## Overview
This program processes a FITS image file to analyze star data and generate plots for peak counts. Specifically, it:

- Reads an image file and identifies stars using the DAOStarFinder algorithm.
- Measures the peak count of each star, corrected for exposure time.
- Fetches magnitude data from the NOMAD catalog based on the filter used (B, V, or R).
- Plots the peak count per second against the catalog magnitude of the stars.
- Fits an exponential curve to the plotted data.

The graph helps users understand the relationship between peak counts and magnitudes for stars in their images. This information is useful for determining the appropriate exposure time to avoid saturating the camera pixels.
