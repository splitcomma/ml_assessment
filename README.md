# Assessment Machine Learning and Statistics, Winter 2023/24

- part 1: [Fisher’s Iris Data Set project](#fisher’s-iris-data-set-project)
- part 2: [Tasks: Machine Learning and Statistics](#tasks-machine-learning-and-statistics)

# Fisher’s Iris Data Set project

## Problem statement

The program file called **project.ipynb** does: 

In the world of data science and machine learning, one of the fundamental tasks is classification.  
The ability to categorize data into predefined classes or groups is a crucial step in solving a wide range of real-world problems.  
In this project, it is embarked on a journey to explore classification algorithms through the lens of the renowned Iris flower dataset associated with Ronald A. Fisher, which serves as an ideal playground for understanding and applying these algorithms.

My project is documented in a notebook, where I systematically delved into the concepts of supervised learning and classification algorithms.  
The Iris dataset, a classic dataset in the field of machine learning, will be the canvas as I dive into this exciting realm.

## Background

The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper. 

The data set consists of 50 samples from each of three species of Iris: Iris setosa, Iris virginica and Iris versicolor.
![3 Iris Species](https://github.com/splitcomma/ml_assessment/blob/main/images/iris_classes.png)

Four features were measured from each sample: the **length** and the **width** of the **sepals** and **petals**, in centimeters.

# Tasks: Machine Learning and Statistics

## Overview

This Jupyter Notebook contains a series of tasks focusing on statistical and numerical methods using Python.  
The tasks cover a range of topics including calculating square roots using Newton's method, performing statistical tests, and analyzing famous datasets like the penguins and iris datasets.  
Each task requires different Python packages and methodologies.

## Tasks
1. Square Root Calculation without Power Operator
Description: Write a function sqrt(x) to approximate the square root of a floating point number x using Newton's method, without the power operator or external packages.
Instructions: Implement Newton's iterative method with the formula: zi+1 = zi - (zi * zi - x) / (2 * zi). Set a threshold for the difference between consecutive guesses.
2. Chi-squared Test on Drink and Biscuit Preference
Description: Perform a chi-squared test using scipy.stats to investigate the association between drink (coffee/tea) and biscuit (chocolate/plain) preferences.
Instructions: Create a contingency table from the survey data and perform the chi-squared test.
3. T-test on Penguins Dataset
Description: Conduct a t-test on the penguins dataset to examine if there's a significant difference in body mass between male and female gentoo penguins.
Instructions: Use scipy.stats.test_ind for the t-test after segregating the data based on penguin gender.
4. Analysis of Setosa Class in Iris Dataset
Description: Analyze the iris dataset to determine if the setosa class is distinctly separable from the other two classes.
Instructions: Visualize the data using scatter plots or other methods to assess the separability of the setosa class.
5. Principal Component Analysis on Iris Dataset
Description: Perform Principal Component Analysis (PCA) on the iris dataset, reducing its dimensions to two.
Instructions: Use PCA from sklearn to reduce dimensions and interpret the results, explaining the purpose of the analysis.


## Usage of the repository:

## Requirements

- Python 3.x: Ensure you have Python 3.x installed. You can download it from python.org.
- Git: Ensure you have Git installed. You can download it from git-scm.com.
- Jupyter Notebook: Ensure you have Jupyter Notebook installed. You can download it from jupyter.org.
- Jupyter Notebook: Install Jupyter Notebook using pip:

```
pip install notebook
```

### Required Libraries:

- scipy: For statistical tests.
- pandas: For data manipulation.
- matplotlib and seaborn: For data visualization.
- sklearn: For data analysis and PCA.
- numpy: For numerical operations.
Run in Anaconda cmd:
```
conda install jupyter seaborn pandas matplotlib numpy scipy scikit-learn
``` 
Or install these libraries using pip:
```
pip install scipy pandas matplotlib seaborn sklearn
```
#### Cloning the repository:
Run in Command Prompt:
```
git clone https://github.com/splitcomma/pands-project.git
```

#### Running the pands-project:
Run in Anaconda cmd:
```
cd pands-project
```
```
python -m notebook
```
Or to run the notebook, navigate to the notebook's directory in the command line and type:
```
jupyter notebook
```
This will open the Jupyter Notebook in your browser.
