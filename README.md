<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.udacity.com/course/data-analyst-nanodegree--nd002'> Udacity Data Analyst Nanodegree </a></h3>
<h4 align="center">Project  3: Communicate-Data-Findings</h4>


**Table of content**

- [Project Overview](#Project_Overview)
- [Installation](#installation)
- [Requirements](#Requirements)
- [Data](#data)
- [Notebooks](#notebooks)
- [HTML](#HTML)
- [Summary_Findings](#findings)
- [Key_Insights](#insights)



## Project_Overview

This project aims to communicate findings revealed from the loan data at prosper using exploratory and explanatory data analysis. The project consists of different parts including pleriminarly wrangling and three types of analysis whereby we try to understand more the dataset and provide valuable insights.


## installation 
```
git clone https://github.com/skevin-dev/communicate-data-findings
jupyter notebook 
```

## Requirements

* pandas 
* numpy 
* Matplotlib
* Seaborn


## data

The dataset comes from Prosper Marketplace Inc., a company that makes loans to people. It includes 113,937 loans, each with 81 variables such as loan amount, borrower rate (or interest rate), current loan status, borrower income, employment status , and many more.

## Notebooks

> All the analysis and examples of implementation can be here in the form of .ipynb file


## HTML 

> All HTML Files can be found in the form of .html file

## findings

> Using univariate exploratory data analysis, histograms were used to analysis the distribution of nominal data. BorrowerAPR and BorrowerRate seem to have the same distribution and nearly normal distribution. Additionaly,Features like DelinquenciesLast7Years and StatedMonthlyIncome seems to be left-skewed. Bar charts were also used to understand qualitative columns. With ProsperRating (Alpha), we can see that "C" category outweighs others, whereby 4 is customer risk sccore with high values in the properscore columns. Borrow home owner status are quite balanced and those who are employed are the one with the most loan compared to the other employee job status. In loan status, it can be seen that people on current loan outweighs others with 49.7% followed by those who completed their loans.

> Using scatterplots, violin plots, pie charts, and bar charts in bivariate analysis interesting insights were discovered.To begin, we observed a strong positive relationship between BorrowerAPR and BorrowerRate. BorrowerAPR values decrease as prosperRating increases, according to the violin plot. Furthermore, using pie charts, we discovered that the highest rating (AA) received the lowest loan, while the lowest rating (HR) received the highest loan.

> During Multivariate exploration, I used various types of plots, including FacetGrid and bar charts, to obtain adequate insights from multiple variables. We discovered that employed people who own a home have high current loans. Furthermore, we discovered that people without homes borrowed loans at a higher rate than people with homes, and that two-year loans were borrowed at a higher rate than one-year and three-year loans.