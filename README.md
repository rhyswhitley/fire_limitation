# fire_limitation
Bayesian parameterisation of the Kelley et al. global fire limitation model.

## how to optimize
Optimization is performed in two jupter notebooks in "notebooks" dir:
* [notebooks/prepare_data.ipynb](https://github.com/rhyswhitley/fire_limitation/blob/master/notebooks/prepare_data.ipynb) prepares data ready for optimization.
* [notebooks/bayesian_inference.ipynb](https://github.com/rhyswhitley/fire_limitation/blob/master/notebooks/bayesian_inference.ipynb) performs the optimzation, and can be used without prepare_data if using csv input data.

## what to install
To run the optimation, you first need jupyter installed ([see here](https://jupyter.org/install.html)), along withthe following libraries:
* numpy as
* pandas
* pymc3 
* scipy
* theano

netCDF4 will also be required to run prepare_data, and matplotlib to perform plotting.

## Reproducing "How contemporary bioclimatic and human controls change global fire regimes"

To run inference used in [this paper](https://rdcu.be/bO6ey), use the [paper1_bayes](https://github.com/rhyswhitley/fire_limitation/tree/paper1_bayes/notebooks) branch. 
To run with the original data, please contact [douglas.i.kelley@gmail.com](mailto:douglas.i.kelley@gmail.com).
