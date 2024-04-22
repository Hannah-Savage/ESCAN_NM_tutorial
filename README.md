# Machine Learning with Normative Modeling Tutorial 
## ESCAN 2024: Normative modelling for affective and cognitive neuroscience: applications and a hands-on tutorial
This repository contains written instructions, links to code, and data used for the Normative Modeling tutorial at  [ESCAN 2024]([https://escan2024.com/]).

## Overview tutorial
In this tutorial you will learn:
1. To create your own normative models using brain imaging data.
2. Interpret and visualize the outputs of the normative models.
3. Use the deviation scores to predict schizophrenia.

This repository is a group effort by [Saige Rutherford](https://twitter.com/being_saige), [Thomas Wolfers](https://twitter.com/ThomasWolfers) and has been updated and edited by [Hannah Savage](https://twitter.com/DrHannahSavage) and [Charlotte Fraza](https://twitter.com/CFraza).

## Prerequisite knowledge
We will be running all of our code in Google Colab Python notebooks. These are essentially Jupyter notebooks run in the :cloud: *cloud* :cloud:. 
Running our code using Colab will save us from dealing with python library installation and virtual environment setup. 
It also ensures that we are all working on the same operating system which makes troubleshooting much easier (since there are only 2 instructors and lots of students)! 

In general, it is assumed that you have some basic experience with Python programming, for an in-depth introduction you can look at the free [Python data science handbook](https://jakevdp.github.io/PythonDataScienceHandbook/). Furthermore, the [neuromatch academy](https://compneuro.neuromatch.io/tutorials/intro.html) has some great resources. 

If you have never used Google Colab before, you can check out an introduction notebook with lots of helpful links here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/notebooks/intro.ipynb)

We will also be using the Pandas library for a lot of our code. There is a great intro to Pandas Colab notebook here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/notebooks/mlcc/intro_to_pandas.ipynb)

Other helpful pandas:panda_face:/plotting:bar_chart: links (not required to do during the practical, just added for those who might need extra Python help):
1. [Pandas cheatsheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
2. [Pandas Selecting/Indexing API](https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html)


## Video
If you are interested in some pre-reading, you can watch an introduction to Normative Modelling lecture, given by [Andre Marquand](https://twitter.com/amarquand?lang=en), here:

[![normative modelling lecture](https://img.youtube.com/vi/8YX1K_ln14k/maxresdefault.jpg)](https://www.youtube.com/watch?v=8YX1K_ln14k&t=3s)


### :warning: Setup instructions for Google Colab :warning:
You can open the Python notebook that we will use in this practical directly from this Github account (the links to the notebook are at the bottom of this Read Me file). Before you open the notebook, make sure you are logged into a Google account. All of the code has been tested using Google Chrome web browser. When you are ready to begin, you will click on the different Tasks with a Google Colab button below. This will launch a new browser tab with the Google Colab notebook. 

Once you are in the Colab notebook tab, in the top right corner you will see a `Connect` (or `Reconnect`) button. Click on this, and a dropdown menu will appear as shown below. Click on `Connect to hosted runtime` this will allow you to run the notebook using Google’s cloud resources, which are likely much faster than your computer. If you would prefer to use your own computer’s resources (this is not recommended and instructors will not be able to help you troubleshoot if you are not running the notebook in the cloud), select `Connect to local runtime`. 

:warning: Note: Sometimes if the notebook is left running for a long time without any activity (i.e. your computer goes to sleep), you will be disconnected from the runtime. In that case, you will need to click on this same button. It will appear as `Reconnect` instead of `Connect`. You will also need to  re-run all code blocks. 

![](presentation/Runtime1.png)

:arrow_right: If you are using the Google Cloud hosted option: in the upper left corner, you will see a button called `Runtime`. Click on `Runtime`, and another dropdown panel will appear (as shown below). Click on `Change runtime type`.

![](presentation/Runtime2.png)

:arrow_right: This box will open, and you can click the  `GPU` option, then click `save`. 

![](presentation/GPU.png)

:arrow_right: In the same menu you used to change the runtime, there are several other optional things you can explore that may make your interaction with the notebook easier. Under ‘Tools’ there is a ‘Settings’ tab, which you can use to change the theme to light or dark mode using the ‘Site’ sub-tab. Then under the ‘Miscellaneous’ sub-tab, you can select Corgi or Kitty mode, and this will make cute animals walk across the top of your screen. There is no practical utility to this whatsoever, and it is for the sole purpose that cute animals spark joy. 

:arrow_right: Also under the ‘Tools’ tab, there is an option to look at Keyboard shortcuts. You don’t need to change any of these, but you can review some of them if you want to learn about speeding up your coding practice. 

![](presentation/keyboard_pref.png)

:arrow_right: In the Colab python notebook, there are 2 types of cells: text cells & ```code cells```. The text cells have plain text in them, that the notebook will not interpret as code. These are the cells that contain the background story & task instructions. The ```code``` cells have a :arrow_forward: play button on the left side. These are the cells that the notebook will run as code. To run a ```code cell```, you can either click on the play button :arrow_forward: on the left side or use ‘Shift + Enter’ (your cursor must be inside the code cell). 
 
### Now you are ready to begin coding :brain:	:computer:! 
### Good luck :four_leaf_clover: and remember to have fun :smiley:! 

Before clicking on the collab button below, make sure you are logged into a Google account and using Chrome or Firefox internet browser (hopefully a current version)

## Tasks
**Task 1: Fitting normative models from scratch** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CharFraza/CPC_ML_tutorial/blob/master/tasks/1_fit_normative_models.ipynb)

**Task 2: Applying pre-trained normative models** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CharFraza/CPC_ML_tutorial/blob/master/tasks/2_apply_normative_models.ipynb)

**Task 3: Interpreting and visualizing the outputs of normative models** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CharFraza/CPC_ML_tutorial/blob/master/tasks/3_Visualizations.ipynb)

**Task 4: Using the outputs (Z-scores) as features in predictive model** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CharFraza/CPC_ML_tutorial/blob/master/tasks/4_post_hoc_analysis.ipynb)

