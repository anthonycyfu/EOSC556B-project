# EOSC556B-project
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/anthonycyfu/EOSC556B-project.git/HEAD)
 Term Project for EOSC 556B - Crosshole Straight Ray Tomography for Karstic Features Identification

Author: Anthony FU


In the notebook in the repository, we focus on the following:

    - How to define the survey
    - How to define the forward simulation
    - How to predict arrival time data
    - How to define the inverse problem (data misfit, regularization, optimization)
    - How to specify directives for the inversion
    - How to plot the recovered model
    - How to add local weights to the regularization term
    - How to use non-linear inversion

## running the notebook 

You can clone the repository using: 
```
git clone https://github.com/anthonycyfu/EOSC556B-project.git
```

Then `cd` into the `EOSC556B-project` directory:

```
cd EOSC556B-project
```

To setup your software environment, we recommend you use the provided conda environment

```
conda env create -f environment.yml
conda activate env_eosc556b
```

You can then launch Jupyter

```
jupyter lab
```

Jupyter will then launch in your web-browser.