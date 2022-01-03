# PROGRAMMING FOR DATA ANALYSIS | PROJECT | 2021/2022
### AUTHOR: ANTE DUJIC
***

This repository contains a Jupyter notebook *bmi_ireland.ipynb*, done as a project for Programming for Data Analysis module on GMIT, Ireland. It also contains this README file with an overview of the mentioned notebook, *requirements.txt* file with a list of necessary libraries to run this project, *dataset.png* image of 20 first rows of the dataset and *bmi_ireland.csv* which is the full simulated dataset.

### HOW TO RUN THIS PROJECT?

1. Clone the repository from the [GitHub](https://github.com/AnteDujic/Programming-for-Data-Analysis_project)
2. Download [Anaconda](https://docs.anaconda.com/anaconda/install/windows/)
3. Download [cmder](https://cmder.net/)
4. Run Jupyter Lab or Jupyter Notebook
5. Open notebook in Jupyter

Alternatively:
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AnteDujic/Programming-for-Data-Analysis_project/HEAD) *click for interactive version*
- [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/AnteDujic/Programming-for-Data-Analysis_project/blob/main/bmi_ireland.ipynb) *click for static version* 

### NOTEBOOK OVERVIEW

The aim of this project is to show a step by step simulation of a dataset of BMI and Alcohol consumption in Ireland. Ireland has one of the highest levels of obesity in Europe, with 60% of adults and over one in five children and young people living with overweight and obesity. [17] Alcohol consumption is often linked to a high weight. Average BMI is increased with an increased level of alcohol consumption in men and women. [4]
<br>
The data is modeled and synthesised using *numpy.random* package in Python. Notebook is separated into the three sections. First section is a Research section, where it is explained what each variable represents and it's real life properties. In second section, Simulation, it is shown how to simulate each of the variables based on the research done. Data Analysis is the last section and contains the analysis of the generated database.

The variables and the methods used to simulate them are shown in the table below:

| VARIABLE | SIMULATION METHOD |
| :- | :- |
| id | library name |
| gender |  numpy choice|
| age |  numpy normal|
| height(cm) | numpy multivariate_normal |
| weight(kg) | numpy multivariate_normal |
| bmi |  formula weight(kg)/height(m)^2|
| alcohol_con(g/pd) | numpy multivariate_normal |
| bmi_class | if condition in bmi |

#### SIMULATED DATASET (first 20 rows)

![](https://github.com/AnteDujic/Programming-for-Data-Analysis_project/blob/main/dataset.png)