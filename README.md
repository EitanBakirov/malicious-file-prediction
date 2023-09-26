# Data Science – Final Project

## Overview

This data science project aims to solve a binary classification problem using static file analysis. The goal is to classify files as either malicious or non-malicious based on a set of features, some of which are known and others are anonymous. The project involves exploratory data analysis, data preprocessing, machine learning model building, and evaluation.

For a more in depth explanation of all our proccess of work you can access "report_english.pdf"/ "report_hebrew.pdf" or the notebook itself "notebook.ipynb".

## Table of Contents

- [Data Science – Final Project](#data-science--final-project)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Project Description](#project-description)
  - [Data](#data)
  - [Methodology](#methodology)
  - [Results](#results)
  - [Usage](#usage)
  - [Authors](#authors)
  - [Contact](#contact)

## Project Description

In this data science project, we were tasked with classifying files as malicious (1) or non-malicious (0) based on various features in the dataset. The project involved:

- Exploratory Data Analysis to understand the data's distribution and correlations.
- Data preprocessing, including handling missing values, dealing with categorical features, and feature engineering.
- Building and evaluating machine learning models, including Random Forest and K-Nearest Neighbors, to select the best model.
- The selected Random Forest model achieved a high AUC score and was used for predictions.

Also, in the folder "Instructions" you can get the full instructions of the project in hebrew and english.

## Data

The dataset contains 60,000 observations classified as malicious or non-malicious files. Some features are known, while others are anonymous. Data preprocessing steps included handling missing values, normalizing data, and dealing with outliers.

## Methodology

We applied exploratory data analysis, including histograms and correlation analysis, to understand feature distributions and relationships. Data preprocessing involved filling missing values, converting categorical features, and feature engineering. We built machine learning models, including Random Forest and K-Nearest Neighbors, using cross-validation and hyperparameter tuning.

## Results

The Random Forest model was selected as the best-performing model with a high AUC score. The model showed a balanced trade-off between precision and recall. Feature importance analysis revealed key features contributing to classification, such as 'Avlength,' 'B,' 'imports,' 'Urls,' and 'file_type_prob_trid.'

## Usage

To reproduce the project's results or use the models just clone the repository and run "notebook.ipynb"

<span style="color:red;"><b>Note:</b></span><br>
It is recommended to use NumPy version 1.23.5 in order to be able to import:

```python
import statsmodels.api as sm
from statsmodels.stats.outliers_influence import variance_inflation_factor 
```
<br>
Before running the project, please use the following command in your terminal or command prompt:
```python
pip install numpy==1.23.5
```

## Authors

- [Eitan Bakirov](https://github.com/EitanBakirov)
- [Yuval Bakirov](https://github.com/YuvalBakirov)

## Contact

For questions or feedback related to the project, please contact Eitan Bakirov at EitanBakirov@gmail.com.
