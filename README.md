# Into to HoloViz

Julia Signell | @jsignell | Head of Open Source at Saturn Cloud

Materials at: https://github.com/jsignell/intro-to-holoviz

## Summary
Learn how to use HoloViz tools to visualize tabular and array data in Python. If want to be able to quickly see what your data look like this talk may help.

## Learner profile
This material is best suited to people who are familiar with Python (or another programming language like R, Matlab, or Julia). If you have encountered Pandas and Numpy and are familiar with running code in a Jupyter notebook even better!

## Learning Objectives
 After attending this, you should be able to:

- Quickly inspect your data using `hvplot`.
- Aggregate large data to the pixel level using `datashader`.
- Produce dashboards that allow others to easily view your outputs using `panel`.


## Running the notebooks

There are two different ways in which you can set up and go through the notebooks. Both of which are outlined in the table below.

|     Method    | Setup | Description |
| :-----------: | :-----------: | ----------- |
| Binder        | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jsignell/intro-to-holoviz/main?urlpath=lab)         | Run the tutorial notebooks on mybinder.org without installing anything locally.       |
| Local install | [Instructions](#Local-installation-instructions)          | Download the notebooks and install the necessary packages (via `conda`) locally. Setting things up locally can take a few minutes.    |


## Local installation instructions

### 1. Clone the repository

First clone this repository to your local machine via:

```
git clone https://github.com/jsignell/intro-to-holoviz
```

### 2. Download conda (if you haven't already)

If you do not already have the conda package manager installed, please follow the instructions [here](https://docs.conda.io/en/latest/miniconda.html). 

### 3. Create a conda environment

Navigate to the `intro-to-holoviz/` directory and create a new conda environment with the required
packages via:

```terminal
cd intro-to-holoviz
conda env create --file binder/environment.yml
```

This will create a new conda environment named "intro-to-holoviz".

### 4. Activate the environment

Next, activate the environment:

```
conda activate intro-to-holoviz
```

### 5. Launch JupyterLab

Finally, launch JupyterLab with:

```
jupyter lab
```