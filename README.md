[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hsma5/9b_forecasting_with_prophet/HEAD)

# HSMA5: Simple forecasting with Prophet


**Welcome to the HSMA forecasting repo (9B)**.  In the second 3 hour class you will be introduced to forecasting applied to operational problems in health and social care using the forecasting package Prophet, from Facebook.

## Module structure

> The module lecture slides are available in this repo, and the lecture is scheduled to take place on the afternoon of 21 February 2023.

## Learning outcomes

**By the end of the class you will have...**

* New tools to appraise and question forecasting studies;
* Hands on experience of manipulating time series in python; and
* Hands on experience of producing simple forecasts using [`prophet`](https://facebook.github.io/prophet/).

## Launch notebooks in Binder

It is possible to run an interact with all of the notebooks in this course without installing anything on your own machine.  Click on the 'launch binder' badge to launch an instance of Jupyter Lab on MyBinder.  Note that all of the code is running in the 'cloud'.  To save any changes to a notebook you will need to go to File -> Download.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hsma5/9b_forecasting_with_prophet/HEAD)

## Setup on Windows

If you wish to use your own machine then please set up in advance of the live lectures on 21 February 2023. 

> [We have provided a video going through the written instructions below.](https://youtu.be/u60CcwZBPYo)

To learn more about environments, you can [watch this brief video](https://www.youtube.com/watch?v=CCqgNbuwMSU).

You are provided with a conda environment (see [`environment_win.yml`](https://github.com/hsma5/9b_forecasting_with_prophet/blob/main/environment_win.yml) within the repo) that you can use to create a new environment and install the necessary dependencies.  To achieve this, follow the in instructions below (which assume that you have not set up an SSH key on your machine).

1. Navigate to https://github.com/hsma5/9b_forecasting_with_prophet in your preferred web-browser and click on the green `<> Code` button then click on `Download ZIP`.

2. Once the ZIP folder has downloaded to your local machine, open it and extract the `9b_forecasting_with_prophet-main` folder within to the desired location on your machine. Open that folder from the extracted location. *Tip: use the mouse cursor to select and copy the full path of the folder i.e., `c:\Users\percy\Desktop\9b_forecasting_with_prophet-main\`*.

3. Launch Anaconda Prompt (<kbd>![Windows Key](http://i.stack.imgur.com/B8Zit.png)</kbd> then typing `Anaconda Prompt` to search for it) and navigate to the folder you've just extracted. This can be done by typing `cd`, followed by a space and then simultaneously pressing <kbd>Shift</kbd> + <kbd>Insert</kbd> (or right mouse click and Paste) then pressing the <kbd>Return</kbd> key. This will change move you to that folder.

4. Now run the following command:

   * `conda env create -f environment_win.yml`

5. Conda will resolve the environment and ask if you wish to install it.  Answer 'y'. Installation will take several minutes.  It installs an environment called `hsma5_forecast9b_win`.  You need to activate it using the command below. *To confirm that new environment has been activate, you will see `hsma5_forecast9b_win` in parenthesis to the left of the prompt.

   * `conda activate hsma5_forecast9b_win`

6. To follow the code along lectures and complete the exercises please use Jupyter-Lab.  To run it enter the following command into your anaconda prompt (making sure you are in the same directory as the files). Jupyter will then open.

   * `jupyter-lab`


# Description of materials.

The module begins with a Prophet theory lecture.  This is deliver using slides that can be found in the main folder (`9b - Forecasting with Prophet.pdf`).

There are four notebooks in the module; three code along files and one exercise file. The solutions will be provided after the live lecture to ensure you maximise your learning opportunities on the day.

## Code along notebooks

During the live session, we'll be working our way through three different notebooks in a code along format. These can be found in the `code_along\` directory. Below is a description of each code along file.

* Code along 1: Preprocessing data to Prophet format (`code_along_1_LIVE.ipynb`)
You will first learn how to wrangle time series data into a format suitable to pass to Prophet.  You will create a reusable function to help with future work.

* Code along 2: Using a basic Prophet model for forecasting (`code_along_2_LIVE.ipynb`)
You will learn how to fit a basic Prophet model, using the default settings, and produce point forecasts and prediction intervals.

* Code along 3: Adding special events to the forecast (`code_along_3_LIVE.ipynb`)
Many health time series contain 'spikey' events where demand surges or drops each year.  You will learn how to use Prophet's built in holidays and add a manual date to a model.  You will also learn how to check if these holidays are important or not.

## Practical exercises notebooks

The exercise notebook can be found in `exercises\` directory.

In the exercise notebook you will work with a different time series and put into practice the skills you have learnt in the code along lectures.

## Solutions to exercises

> Solutions to practical exercises will be released following the live lecture, scheduled for 21 February 2023.

