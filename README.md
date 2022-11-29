[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hsma4/module_9_b/HEAD)

# Simple forecasting with Prophet
## HSMA5
-----

**Welcome to the second in our series of HSMA forecasting classes**.  In this 3 hour class you will be introduced to forecasting applied to operational problems in health and social care.  We will make use of the forecasting package Prophet.

## Module structure

> The module lectures are delivered as a series of Youtube lectures. Links below.

1. [A lecture introducting the theory of forecasting with Prophet](https://www.youtube.com/watch?v=tV2_iLr7lsc )
2. A series of short code-along lectures in Jupyter notebooks
   * [Preprocessing](https://www.youtube.com/watch?v=DXG9aIECtp4)
   * [Fitting and predicting with a basic model](https://youtu.be/DTm6a13IiSg)
   * [Adding holidays and special events](https://youtu.be/5MV1coh63oA)
3. A 60 minute practice exercise to give you experience of preprocessing data ready to use in prophet and a how to automatically fit prophet models

## Learning outcomes

**By the end of the class you will have**

* New tools to appraise and question forecasting studies
* Hands on experience of manipulating time series in python
* Hands on experience of producing simple forecasts using Prophet.

## Launch notebooks in Binder

It is possible to run an interact with all of the notebooks in this course without installing anything on your own machine.  Click on the 'launch binder' badge to launch an instance of Jupyter Lab on MyBinder.  Note that all of the code is running in the 'cloud'.  To save any changes to a notebook you will need to go to File -> Download.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hsma4/module_9_b/HEAD)

## Setup on Windows

If you wish to use your own machine then please set up in advance of the module. 

> [We have provided a video going through the instrutions below.](https://www.youtube.com/watch?v=H4eopptC_Tw)

You are provided with a conda environment (see environment_win.yml) that you can use to install the dependencies.  To install follow these instructions.  

1. Open git bash, navigate to the directory you wish to use and clone the repository.  The clone command is:

* `git clone https://github.com/hsma4/module_9_b.git`

2. Open an anaconda prompt and navigate to the directory containing the course files.  Run the following command

   * `conda env create -f environment_win.yml`

3. Conda will resolve the enviornment and ask if you wish to install it.  Answer 'y'. Installation will take several minutes.  It installs an environment called `hsma5_forecast9b_win`.  You need to activate it.

   * `conda activate hsma5_forecast9b_win`

4. To follow the code along lectures and complete the exercises please use Jupyter-Lab.  To run it enter the following command into your anaconda prompt (making sure you are in the same directory as the files)

   * `jupyter-lab`

Jupyter will then open.


# Description of materials.

The module begins with a Prophet theory lecture.  This is deliver using slides that can be found in `slides\`

There are four notebooks in the module.  Each is split into a student version and a solution version.  The student notebooks require code to be entered (e.g. code along and exercises).  The solution notebooks contain example solutions and code.

## Code along notebooks

During the live session, we'll be working our way through three different notebooks in a code along format. These can be found in the `code_along_lectures/` directory. Below is a description of each code along file.

* Code along 1: Preprocessing data to Prophet format (code_along_9a_1)
You will first learn how to wrange time series data into a format suitable to pass to Prophet.  You will create a reusable function to help with future work.

* Code along 2: Using a basic Prophet model for forecasting (code_along_9a_2)
You will learn how to fit a basic Prophet model, using the default settings, and produce point forecasts and prediction intervals.

* Code along 3: Adding special events to the forecast (code_along_9a_3)
Many health time series contain 'spikey' events where demand surges or drops each year.  You will learn how to use Prophet's built in holidays and add a manual date to a model.  You will also learn how to check if these holidays are important or not.

## Practical exercises notebooks

The exercise notebook can be found in `exercises\` directory.

In the exercise notebook you will work with a different time series and put into practice the skills you have learnt in the code along lectures.

The notebook also provides some **optional advanced exercises** where you can experiment with Prophet's built in cross-validation tools and compare results with a Naive benchmark method.

## Solutions to exercises

> These notebooks provide example solutions to the problems set.  Feel free to work through them.  We all learn in different ways. It is up to you how you choose to learn either by having a go at the exercises or by working through the code provided.  Remember you can always try the code with your own data!  Good luck.



