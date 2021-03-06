# Matplotlib Case (Power of Plot Challenge Homework Project)

Homework Assignment, Data Science and Visualization Boot Camp (Northwestern University)

![GitHub last commit](https://img.shields.io/github/last-commit/OlegRyzhkov2020/matplotlib-challenge)
![GitHub top language](https://img.shields.io/github/languages/top/OlegRyzhkov2020/matplotlib-challenge)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)
[![HitCount](http://hits.dwyl.com/OlegRyzhkov2020/matplotlib-challenge.svg)](http://hits.dwyl.com/OlegRyzhkov2020/matplotlib-challenge)
![GitHub watchers](https://img.shields.io/github/watchers/OlegRyzhkov2020/matplotlib-challenge?label=Watch&style=social)
![GitHub followers](https://img.shields.io/github/followers/OlegRyzhkov2020?label=Follow&style=social)

## DataSet Description and Basic Summary Analysis

* The most recent animal study observed 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. Exploring and summarizing results should include:
    1. Clean data
    2. Exploratory analysis and summary statistics
    3. Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
    4. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
    5. Gnerate a box and whisker plot of the final tumor volume for all four treatment regimens
    6. Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.

## Dataset observations and inferences

#### 1: Graphical representation of a matrix of distances

![dendrogram](images/dendrogram.png)

![ecdf_chart](images/ecdf.png)

#### 2: Female vs male mice distribution

![histogram](images/distribution.png)

#### 3: Ramicane and Capomulin show greater decrease in tumor volume

![Drug Regimen table](images/stat_table.png)

![Box plot](images/boxplot.png)

#### 4: Regression model
* Linear regression (mouse weight vs average tumor volume for the Capomulin regimen)

![Swamp plot](images/regression.png)

* Formulating and Simulating a Hypothesis

  - The observed data: Capomulin and Ramicane Drug Regimens
  - Null hypothesis: The tumor volume is not significantly affected by the chosen Drug Regimen (Capomulin vs Ramicane)
  - p value is greater than significance level - we can not reject the null hypothesis

#### 5: Further research questions
* How Drug Regimen treatment is affected by the mouse weight

![Swamp plot](images/weight_distribution.png)

![Swamp plot](images/swampplot.png)

## Contacts
[Find Me on
LinkedIn](https://www.linkedin.com/in/oleg-n-ryzhkov/)
