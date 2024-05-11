# 📈 Sourcing Cost Prediction Project 

## Overview 📊
In this project, we aim to predict the sourcing costs for different product combinations using regression analysis. By leveraging machine learning techniques, we'll uncover insights into the factors influencing sourcing costs and build models to improve cost estimation accuracy.

https://github.com/Harsh-Ratna/Harsh_Ratna_AIML_Assessment/blob/main/output/Actual%20vs%20Predicted%20Values%20Random%20Forest.png
<p align='center'><a href="https://github.com/Harsh-Ratna/Harsh_Ratna_AIML_Assessment/blob/main/output/Actual%20vs%20Predicted%20Values%20Random%20Forest.png" target="blank"><img align="center" src="https://github.com/Harsh-Ratna/Harsh_Ratna_AIML_Assessment/blob/main/output/Actual%20vs%20Predicted%20Values%20Random%20Forest.png" height="400" /></a></p>

## Dataset 📋
The dataset used for this project contains the following columns:
- Product Name
- Manufacturer
- Area Code
- Sourcing Channel
- Product Size
- Product Type
- Month of Sourcing
- Sourcing Cost
  
Except the target variable (Sourcing Cost) all the other features are categorical in nature. Month of Sourcing Column indicates the month in which the product combination is sourced.
The Shape of the original Train Data is (550176, 8).

## Methodology 🔍
1. **Data Exploration and EDA:** Explore the dataset to understand variable distributions and identify key insights.
2. **Data Preprocessing:** Cleanse and preprocessing data (Removing Outliers, Renaming column, Transforming data etc.)
3. **Feature Engineering:** Extract meaningful features and engineer new ones to enhance model performance.
4. **Model Selection and fine-tuning:** Experiment with different regression models such as Linear Regression, Random Forest, and Gradient Boosting to find the best fit.
5. **Model Evaluation:** Evaluate model performance using metrics like Mean Absolute Error (MAE) and R-squared to assess accuracy and generalization capability.
6. **Interpretation:** Interpret model coefficients and feature importance to gain actionable insights into cost drivers. 📈

## Files 📂
- `data`: Contains the dataset in csv format used for this project.
- `Source Code`: Contains the jupyter notebook code for Data Analysis and Data Modelling.
- `Data_Exploration_and_Analysis.ipynb`: Python Notebook for Exploration, Univariate, Multivariate and in-depth Analysis of data.
- `Data_Modelling.ipynb`: Python notebook concerned with application of different Models, fine-tuning and visualization of results.

## Results 📈
R2 Scores:
<p align='center'><a href="https://github.com/Harsh-Ratna/Harsh_Ratna_AIML_Assessment/blob/main/output/R2%20Score%20Comparison%20of%20different%20Models.png" target="blank"><img align="center" src="https://github.com/Harsh-Ratna/Harsh_Ratna_AIML_Assessment/blob/main/output/R2%20Score%20Comparison%20of%20different%20Models.png" height="500" /></a></p>

Errors:

<p align='center'><a href="https://github.com/Harsh-Ratna/Harsh_Ratna_AIML_Assessment/blob/main/output/Error%20Comparison%20of%20Models.png" target="blank"><img align="center" src="https://github.com/Harsh-Ratna/Harsh_Ratna_AIML_Assessment/blob/main/output/Error%20Comparison%20of%20Models.png" height="500" /></a></p>

## Conclusion 🎉
In conclusion, the Sourcing Cost Prediction Project provides valuable insights into optimizing procurement processes and improving cost estimation accuracy. Let's continue innovating and driving positive change together! 🌟

## Acknowledgements 🙏
- Special thanks to all contributors and collaborators who made this project possible. Together, we're shaping the future of procurement! 🌍


