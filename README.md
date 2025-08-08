# Data Analytics with R – FIN 550 (UIUC, Spring 2025)

This repository contains lecture materials, lab assignments, and datasets from **FIN 550 – Data Analytics**, completed during my graduate studies at the **University of Illinois Urbana-Champaign**.  
The course combined theoretical concepts with practical implementation in **R**, focusing on reproducible data analysis, machine learning, and causal inference.

---

## Key Topics Covered
- R programming and RStudio environment
- Data wrangling and cleaning with `tidyverse` (dplyr, tibble, readr)
- Exploratory Data Analysis (EDA) and descriptive statistics
- Data visualization with `ggplot2`
- Machine learning concepts: bias-variance tradeoff, cross-validation
- Regression models: linear, multiple, logistic
- Regularization methods: LASSO
- Tree-based models: decision trees, bagging, random forest, boosting
- Neural networks basics
- Statistical inference and hypothesis testing
- Causal inference methods:
  - Randomized experiments
  - Difference-in-differences (DiD)
  - Regression discontinuity (RD)
- AWS EC2/S3 for cloud-based data analysis
- Reproducible workflows with R Markdown

---

## Tools & Technologies
- **Languages:** R  
- **Libraries:** tidyverse, dplyr, ggplot2, readr, tibble  
- **Platforms:** RStudio, R Markdown  
- **Cloud:** AWS EC2, AWS S3  
- **Data formats:** CSV, RData, HTML  

---

## Repository Structure & Module Descriptions

| Module | Topic | Description |
|--------|-------|-------------|
| 01 | Intro to AWS & RStudio | [AWS EC2/S3 setup for RStudio](labs/lab-01-instructions.html) |
| 02 | Intro to R Programming | [Data types, vectors, and lists in R](labs/lab-02.html) |
| 03 | Data Wrangling | [Using `dplyr` and `tibble` for filtering, joining, and summarizing data](labs/lecture-03-tryit.Rmd) |
| 04 | Data Exploration | [Descriptive statistics, sorting, grouping, and exploratory analysis](labs/lecture-04-tryit.Rmd) |
| 05 | Data Visualization | [Customizing plots with `ggplot2`](labs/lab-05.Rmd) |
| 06 | ML Bias-Variance | Understanding bias-variance tradeoff, underfitting vs overfitting |
| 07 | Linear Regression | [Building and interpreting linear regression models in R](labs/lecture-07-tryit.Rmd) |
| 08 | Multiple Linear Regression | Multivariate modeling, interactions, and model diagnostics |
| 09 | Logistic Regression | Classification problems, odds ratios, and confusion matrices |
| 10 | Cross-Validation | k-fold CV, training/testing splits, and model evaluation metrics |
| 11 | Variable Selection | Stepwise selection, adjusted R², AIC/BIC criteria |
| 12 | LASSO Regression | Regularization techniques for feature selection and overfitting control |
| 13 | Regression Trees | Decision tree structure, splitting criteria, and visualization |
| 14 | Bagging, Random Forest, Boosting | [Ensemble learning methods to improve model performance](labs/lab-14-instructions.html) |
| 15 | Neural Networks | [Basic NN structure and training in R](labs/lab-15-instructions.html) |
| 16 | Causal Analysis | Introduction to causal inference concepts and frameworks |
| 17 | Statistical Inference | Hypothesis testing, p-values, and confidence intervals |
| 18 | Randomized Experiments | Experiment design, treatment/control groups, and randomization |
| 19 | Randomized Limitations | Internal vs external validity, threats to validity |
| 20 | Workplace Wellness Study | Real-world RCT case study and data interpretation |
| 21 | Difference-in-Differences | Pre/post treatment analysis for causal effect estimation |
| 22 | DiD Estimation | Implementing DiD models in R with fixed effects |
| 23 | Regression Discontinuity | Sharp and fuzzy RD designs, cutoff rules, and visualization |
| 24 | RD Estimation | Local vs global RD estimation, bandwidth selection, and model fitting |

---

## Example Labs
- **[Lab 01](labs/lab-01-instructions.html):** AWS EC2/S3 setup for RStudio  
- **[Lab 02](labs/lab-02.html):** Data types, vectors, and lists in R  
- **[Lab 03](labs/lecture-03-tryit.Rmd):** Data wrangling with tibbles and joins  
- **[Lab 05](labs/lab-05.Rmd):** Advanced data visualization (custom ggplot2 plots)  
- **[Lab 14](labs/lab-14-instructions.html):** Bagging, Random Forest, Boosting implementation  
- **[Lab 15](labs/lab-15-instructions.html):** Neural network modeling in R  
- **Labs 21–24:** Applied causal inference with DiD and RD methods  

---

## Datasets Used
- [manager.csv](datasets/manager.csv) – Employee survey data  
- [exe.csv](datasets/exe.csv) – Executive performance data  
- [ameshousing.csv](datasets/ameshousing.csv) – Ames Housing dataset for regression models  
- [cleaned_Freddie_Mac.Rdata](datasets/cleaned_Freddie_Mac.Rdata) – Freddie Mac mortgage data  

---

## Skills Gained
- Data cleaning, transformation, and visualization  
- Building statistical and machine learning models  
- Performing cross-validation and model selection  
- Implementing causal inference methods in R  
- Creating reproducible analysis reports in R Markdown  
- Managing cloud-based analysis environments (AWS)  

---

## About the Course
- **Course:** FIN 550 – Data Analytics  
- **Institution:** University of Illinois Urbana-Champaign  
- **Term:** Spring 2025  
- **Instructor:** [Add Name if needed]  

---

## License
This repository is for educational and portfolio purposes only.  
Course materials © University of Illinois Urbana-Champaign.
