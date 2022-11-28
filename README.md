[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hsma4/module_9_a/HEAD)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/release/python-360+/)

# An introduction to forecasting
# HSMA5 - 2023

**Welcome to the HSMA forecasting class**.  In this 3 hour class you will be introduced to forecasting applied to operational problems in health and social care.

## Course structure

1. A lecture introducting you to the theory and practice of forecasting
2. A series of short code-along lectures in Jupyter notebooks
3. Two 20 minute practical exercises to give you experience of visualising time series and producing simple forecasts. 

## Learning outcomes

**By the end of the class you will have**

* New tools to appraise and question forecasting studies
* Hands on experience of manipulating time series in python
* Hands on experience of producing simple benchmark forecasts using the [`forecast-tools`](https://pypi.org/project/forecast-tools/) python package.

## Setup for the course

You are provided with a conda environment (see binder/environment.yml) that you can use to install the dependencies.  To install follow these instructions.

1. Open an anaconda prompt (or terminal on Mac and Linux) in the same directory as the course files.  Run the following commands

   * `conda update conda`
   * `conda env create -f binder/environment.yml`

2. Conda will resolve the enviornment and ask if you wish to install it.  Answer 'y'. Installation will take several minutes.  It installs an environment called `hsma5_forecast`.  You need to activate it.

   * `conda activate hsma5_forecast`

3. To follow the code along lectures and complete the exercises please use Jupyter-Lab.  To run it enter the following command into your anaconda prompt or terminal (making sure you are in the same directory as the files)

   * `jupyter-lab`

Jupyter will then open.


# Launch Notebooks in Google Colab

If you are experiencing issues with Jupyter-Lab on your personal computer then you can also run the notebooks in Google Colab.  Use the links below to launch them

> Note you require a Google account to use Colab.

## Code along lectures
* Code along 1: Loading time series using pandas [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma4/module_9_a/blob/main/code_along_lectures/01_pandas_time_series.ipynb)
* Code along 2: Exploring time series [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma4/module_9_a/blob/main/code_along_lectures/02_exploring_ts.ipynb)
* Code along 3: Simple forecasting [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma4/module_9_a/blob/main/code_along_lectures/03_benchmark_forecasts.ipynb)


## Practical Exercises
* Exercise 1: Exploring time series [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma4/module_9_a/blob/main/exercises/Practical_1.ipynb)
* Exercise 2: Simple forecasting [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma4/module_9_a/blob/main/exercises/Practical_2.ipynb)

## Solutions to Exercises

> These notebooks provide example solutions to the problems set.  Feel free to work through them.  We all learn in different ways. It is up to you how you choose to learn either by having a go at the exercises or by working through the code provided.  Remember you can always try the code with your own data!  Good luck.

* Exercise 1: Exploring time series [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma4/module_9_a/blob/main/exercises/Practical_1_SOLUTIONS.ipynb)
* Exercise 2: Simple forecasting [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma4/module_9_a/blob/main/exercises/Practical_2_SOLUTIONS.ipynb)

