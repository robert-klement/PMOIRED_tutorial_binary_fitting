# PMOIRED Binary Fitting Tutorial

This repository contains `binary_fitting_tutorial.ipynb`, a short hands-on tutorial for fitting binary star models to optical interferometry data with `pmoired`.

The notebook walks through:
- inspecting calibrated `V2` and `T3PHI` data for binary signatures,
- running model fits (`doFit`) and binary grid searches (`gridFit`),
- visualizing grid-search significance (`showGrid`),
- estimating companion detection limits for non-detections (`detLim`).

Data files used in the examples are included in the `data/` directory.

## Quick start

1. Install Python dependencies: `numpy`, `matplotlib`, and `pmoired`.
2. Launch Jupyter and open `binary_fitting_tutorial.ipynb`.
3. Run the notebook cells in order.
