# Exploring Scipy.stats and Scikit-Learn python packages
## Project Description
In the repository are two jupyter notebooks (.ipynb) one for each of the 2 python packages. In these notebooks I explore various functions available from Scipy.Stats and Scikit-learn. 

### A background on each of the packages
#### Scikit-learn
Machine learning is a technique used in data analysis that performs model building with very little programming input. It is a branch of artificial intelligence based on the idea that machines can learn from data to predict outcomes or identify patterns and make decisions with minimal human intervention. Regression - Linear/ polynomial
Classification

#### Scipy.Stats
Statistics is an extremely important area of data analysis. It is best described as the science of collecting, organising, analysing, interpreting and presenting data hence it's importance in the field of data analysis. Scipy.Stats is one part of the Scipy library designation to statistics. It contains a large number of probability distributions, correlation functions and statistical tests to name just a few. It is reliant on the ubiquitous Numpy package in Python. 

## Installation
I personally installed the popular Anaconda data science package which contains a very large number of popular Python packages including jupyter notebooks. However the option to run the notebooks without Anaconda is detailed below. First clone the notebook from Github to your own machine so that all files are downloaded. You can either clone with https/ ssh or you can download a zip file to you computer. 

#### Install Python and Jupyter Notebook without Anaconda  
* The first step is to install Python on your machine from the following link. https://www.python.org/downloads/. Be sure to select "Add Python to path". I used Version 3.8.5 so probably best to download that version to ensure compatibility.
* Next open the command prompt on Windows, or Terminal on Mac and run the command `python -m pip install -upgrade pip`. This will upgrade the pip package for installing the required Python pacakges and Jupyter Notebook
* Next run the command `python -m pip install jupyter`. This will install Jupyter Notebook on your machine.
* To open Jupyter Notebook you can run the command `Jupyter Notebook` in the command prompt and it will automatically open in the browser. (It is best to navigate to the directory where the notebooks are located before you run Jupyter Notebook)
* In the repository is a requirements.txt file. This contains the information for each of the Python modules which are used in both notebookes.
* In command prompt or terminal run the command `pip -r install requirements.txt`. This will install the packages locally on your machine. Note these are all trusted Python sources and are not very large.
* Once this is done you are ready to view the notebooks.


#### How to use with Anaconda  
* Clone the repository your machine.
* In terminal or command prompt navigate to the repository and if you feel you are out of date with certain packages you can run the command `pip -r install requirements.txt`. This will update your packages to the version used in my notebooks.
* Next run Juypter Notebook or Jupyter Lab to start exploring the notebooks


#### Alternative Option
* An alternative option is to view the notebooks online using nbviewer. Just click either of the hyperlinks below to redirect to a nicely rendered version of the notebook in your browser  
[scikit-learn.ipynb](https://nbviewer.org/github/killfoley/ML-and-Stats/blob/main/scikit-learn.ipynb)  
[scipy-stats.ipynb](https://nbviewer.org/github/killfoley/ML-and-Stats/blob/main/scipy-stats.ipynb)

## Running the project
Note: Each of the notebooks have been linked to the github url of the datasets so there is no need to store the data folder locally on your machine if you don't want to. 
* The project can be run by selecting `Kernel` in the top toolbar a dropdown will appear, select `Restart & Run All`. If all the cells run without an error this will confirm your installation process worked.
* Each of the notebooks is a step by step demonstration of general data analysis techniques such as data visualisation and manipulation, and algorithms from Scikit-Learn and Scipy Stats.




