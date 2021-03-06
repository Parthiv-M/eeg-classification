## Pre-requisistes

To get started, please ensure that you have at least Python 3.6.9 installed on your system. If not, install it from [here](https://www.python.org/downloads/). Also ensure you have `pip` installed on your system. It helps to handle environments and packages for your project. Usually, `pip` is automatically installed if you download and install Python correctly, but in case you do not have it, install it from [here](https://pip.pypa.io/en/stable/installation/).

To check if you have python installed, run `python3 -V` in a terminal window. If it returns the version, then you are all set to go!

## Create a Virtual Environment

A virtual environment helps separate packages from other projects as well as gives a dedicated space for your code to run. Firstly, verify that either pip or conda exists on your system by running either conda -V or pip -V. If not, correct your Python installation.

To create a virtual environment with pip follow these steps:
- Install virtualenv with the following command `pip install virtualenv`
- After it is installed, run `virtualenv <env_name>` to create your virtual environment for this project. Replace `<env_name>` with any name of your choice
- After the environment is created, run `source <env_name>/bin/activate` to activate your environment
- Once the environment is created, you should see your environment name as a prefix to your prompt in your terminal, as shown below
```
(env_name) parthiv@laptop: ~/$
```

## Installing Packages

All the modules required for running this project are present in the `requirements.txt` file. To install these packages, run `pip install -r requirements.txt`. That should install all the modules required for this implementation.

## The Implementation

This is the easiest part. All the code is present in two Jupyter notebooks.
- [This](https://github.com/Parthiv-M/eeg-classification/blob/e8dd387e3245513738b9137ebf5cd74b775310e2/anderson_1996/EEG%20Preprocessing%20and%20Feature%20Extraction.ipynb) notebook contains the code for pre-processing and feature extraction
- [This](https://github.com/Parthiv-M/eeg-classification/blob/e8dd387e3245513738b9137ebf5cd74b775310e2/anderson_1996/Neural%20Network.ipynb) notebook contains the code for the 20-0 neural network, as implemented by us 