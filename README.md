# Pymaceuticals Inc. Data Analysis

## Introduction
This repository contains the resources csv files, code and analysis for the Pymaceuticals Inc. data analysis. It involves exploring and analyzing data related to a pharmaceutical company's study on potential treatments for a form of skin cancer.

## Dataset Overview
The dataset used in this analysis contains information on 249 mice, each with SCC tumors, and their response to various drug regimens. The study spanned 45 days, during which tumor development was monitored and measured. The primary focus of this analysis is to compare the effectiveness of Capomulin, one of the drugs of interest, against other treatment regimens.

## Repository Structure
This repository is organized into several sections, each corresponding to a specific task or aspect of the data analysis:

  **01_prepare_data**: The Python code contains data preprocessing, including merging datasets, identifying and removing duplicate mouse data, and ensuring data cleanliness.

  **02_summary_statistics**: The calculation and presentation of summary statistics for each drug regimen, including mean, median, variance, standard deviation, and SEM of tumor volume has been done.

  **03_create_charts**: The code includes  bar charts to display the total number of timepoints for each drug regimen and pie charts to illustrate the distribution of female versus male mice in the study.

  **04_quartiles_outliers**: In this Python code, you'll find a section related to quartile calculation, outlier identification, and the generation of box plots to visualize the distribution of final tumor volume for selected treatment regimens.

  **05_line_scatter_plots**: A section dedicated to generating a line plot showing tumor volume versus timepoint for a mouse treated with Capomulin and a scatter plot illustrating the relationship between mouse weight and tumor volume for the entire Capomulin regimen.

  **06_correlation_regression**: This section contains calculating the correlation coefficient and performing linear regression to analyze the relationship between mouse weight and tumor volume within the Capomulin regimen.

## Instructions for Studying the Code
Follow these steps:

- Execute the code in a Jupyter Notebook or JupyterLab environment to replicate the analysis and generate the same plots and results.
- Make sure all libraries and modules are installed and imported.
- Refer to the comments and markdown cells within the notebooks for explanations and insights about the analysis and findings.

## Observations and Inferences
At the beginning of the notebook, you'll find a section with key observations and inferences drawn from the data analysis. These observations highlight the significant findings and insights obtained from the analysis.

