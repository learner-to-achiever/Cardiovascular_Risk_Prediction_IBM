# Cardiovascular-Risk-Prediction

<br>
<div align="center">

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

<br>

[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/iamwatchdogs?tab=repositories&q=&type=public&language=&sort=)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/iamwatchdogs/Cardiovascular-Risk-Prediction/pulls)
[![GitHub issues](https://img.shields.io/github/issues/iamwatchdogs/Cardiovascular-Risk-Prediction.svg)](https://github.com/iamwatchdogs/Cardiovascular-Risk-Prediction/issues)
[![GitHub pull-requests merged](https://badgen.net/github/merged-prs/iamwatchdogs/Cardiovascular-Risk-Prediction)](https://github.com/iamwatchdogs/Cardiovascular-Risk-Prediction.js/pulls?q=is%3Amerged)
[![GitHub release](https://img.shields.io/github/release/iamwatchdogs/Cardiovascular-Risk-Prediction)](https://GitHub.com/iamwatchdogs/Cardiovascular-Risk-Prediction/releases/)
[![License](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)

</div>
<br>

## Problem statement

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes. Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors. 

## Solution Approach

First, I have started preparing for the model training phase by cleaning and preprocessing the dataset. The dataset itself is clean and only needs a few transformations of categorical data into numerical data for the models to be trained. After the transformation, I split the data for training and testing purposes. I have trained a few models using various algorithms like **"LogisticRegression"**, **"Decision Tree"** and **"Random Forest Classification"**. At the end of the training, I compared the accuracy of each model and concluded that the model trained using **"Random Forest Classification"** does a better job of classifying the required attribute and resolving the problem statement.

## Setting up in your local system

You can start by forking the repo into your profile just by clicking the fork button above or just [click here](https://github.com/iamwatchdogs/Cardiovascular-Risk-Prediction/fork).

Now, just clone the repo into your local system using the following command:

```bash
git clone https://github.com/<your-github-user-name>/Cardiovascular-Risk-Prediction.git
```

After cloning the repository, you can navigate through the project in any of the following ways:

- [Using Miniconda environment](#using-miniconda-environment)
- [Jupyter through Anaconda Navigator](#jupyter-through-anaconda-navigator)
- [Google Colab](#using-google-colab)

### Using Miniconda environment

Make sure you have Miniconda using the following command:

```bash
conda --version
```

If you don't have Miniconda installed within your system, then you can just install it from their [official page](https://docs.anaconda.com/free/miniconda/).

You can create a new environment using the dependencies config [`environment.yml`](./environment.yml). Use the following command:

```bash
conda env create -f environment.yml
```

Now that you have created the environment, you have to activate the environment using the following command:

```bash
conda activate cardiovascular-risk-prediction
```

Now you can just use it either in VS code or just host the Jupyter Notebook.

> If you're using the project through VS code you can just selected the Kernel environment as `cardiovascular-risk-prediction`. All you have to do is select
>
> - Select the _"Select Kernel"_ button on the top.
> - Choose _"Python Environment"_ option and choose the conda environment named `cardiovascular-risk-prediction`.

> If you want to host it the Jupyter Notebook, just use the following command:
>
> ```bash
> jupyter notebook
> ```
>
> Now the Jupyter Notebook server is up and running within you system on <localhost:8888>.
> And now, you can access the Jupyter Notebook on <http://localhost:8888/notebooks/notebook.ipynb>.

### Jupyter through Anaconda Navigator

All you have to do is install Anaconda Navigator from the [official website](https://www.anaconda.com/download) and Jupyter Notebook will included within the installation. and all you do is search for Jupyter Notebook within your search utility like the start bar in the Windows. Just start up the Jupyter Notebook, navigate through the file location and open the Jupyter Notebook.

### Using Google Colab

All you have to do is import this project into [Google Colab](https://colab.research.google.com/) and you're done. Just visit their website import the notebook using the GitHub option and you have the whole project within your environment.