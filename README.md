# PMOIRED Binary Fitting Tutorials

This repo has three PMOIRED notebooks for binary-star interferometry:

1. [`simulating_binary_data_tutorial.ipynb`](simulating_binary_data_tutorial.ipynb)  
   Simulate VLTI/PIONIER binary data (clean + noisy) to see expected `V2` and `T3PHI` behavior.
2. [`binary_fitting_tutorial1.ipynb`](binary_fitting_tutorial1.ipynb)  
   Continuum binary fitting with CHARA MIRC-X/MYSTIC data using `doFit`, `gridFit`, `showGrid`, and `detLim`.
3. [`binary_fitting_tutorial2.ipynb`](binary_fitting_tutorial2.ipynb)  
   Advanced GRAVITY spectro-interferometric fitting (Br-gamma example on HR 6819).

Example OIFITS files are in [`data/`](data/).

## Quick start

1. Install `numpy`, `matplotlib`, and `pmoired`.
2. Open the notebooks in Jupyter.
3. Run cells top to bottom.
