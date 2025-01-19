# APANProjects
Showcase of applied analytics work for prospective employers. Includes ML techniques like Trees, Regressions, and NLP analysis as well.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Licensing Issues](#licensing-issues)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Cleaning and Model Preparation](#data-cleaning-and-model-preparation)
- [Modeling Approaches and Tuning](#modeling-approaches-and-tuning)
- [Results](#results)
- [Conclusion](#conclusion)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)

## Project Overview
These projects are Kaggle-based competitions with no prize payouts which are showcases of my first forays into data science. I have addressed many of the common issues that appear in ML problems like class imbalances, data cleaning/preperation, model selection and validation concepts. MLModel focuses on price prediction using an ensemble model of XGBoost & Regression tactics to predict car prices. SampleClassifier is a classification focused dataset that focuses on eligibility for a government program. 

## Data Sources
The data sources are found on kaggle link here: https://www.kaggle.com/datasets Most are for academic purposes which fully comply with licenses. 

## Licensing Issues
Data sets are open-sourced and suitable for educational purposes.

## Exploratory Data Analysis (EDA)
EDA for Car Analysis shows us relationships between the actual configurations of a car and performance which have some relationships with price. 

![image](https://github.com/user-attachments/assets/59bc9d85-1c2b-419f-9485-da2f12426d9f)

EDA for SampleClassifier shows many different cars where the mileage on a full charge are considered. Preliminary analysis suggested that Electric Range is highly correlated with CAFV Eligiblity Simple.

        
  EV_no.      Electric Range  Base MSRP  Legislative District CAFV Eligibility Simple  
92676              56          0                  40.0                Eligible  
92677              21          0                  15.0            Not Eligible  
92678              17          0                  21.0            Not Eligible  
92679              23          0                   8.0            Not Eligible  
92680              17          0                  21.0            Not Eligible  
92681              21          0                  15.0            Not Eligible  
92682              23          0                   8.0            Not Eligible  
92683             100      32995                  28.0                Eligible  
92684             100      32995                   6.0                Eligible  
92685               6          0                   8.0            Not Eligible  
92686               6          0                  31.0            Not Eligible  
92687               6          0                   8.0            Not Eligible  
92688               6          0                  31.0            Not Eligible  
92689               6          0                  31.0            Not Eligible  
92690               6          0                   8.0            Not Eligible  
92691               6          0                   8.0            Not Eligible  
## Data Cleaning and Model Preparation
Any column that had over 10% missing values was excluded because imputation was impractical at that point. SimpleClassifier yielded no missing values. 

## Modeling Approaches and Tuning
I used ensemble models for most of my modeling approaches because I felt that was the most appropriate for the problems discussed. 

## Results
I had some moderate results but I felt like my results could be improved. 

## Conclusion
My approach was definitely not the best way to address these problems as there were most steps I could have taken like cross-validation, data preperation steps, and other misc. approaches I did not know at the time. I hope to document these projects as a guide for what my baseline performance was and improve upon design choices, ensure data quality and other changes. 

## Installation and Setup
Instructions on how to install and set up the project.

## Usage
How to use the project's code and scripts.
