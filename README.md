# EPS Nowcasting with Lasso Regression
This repository provides a method for nowcasting the Earnings Per Share (EPS) of Apple Inc. using Lasso Regression. The predictive model leverages Google Trends data for specific keywords related to Apple's business.

## Overview
Nowcasting is the process of predicting economic variables in the present or the very near future. In this project, we focus on nowcasting the EPS of Apple, a leading technology company, by incorporating Google Trends data. Google Trends provides insights into the popularity of search terms over time, which can be indicative of public interest and potential impact on financial markets.

## Methodology
We employ Lasso Regression, a linear regression technique with L1 regularization, to build a predictive model. The key idea is to select a subset of relevant keywords from Google Trends to construct the feature set (X) and predict the EPS (y) of Apple. L1 regularization helps in feature selection, enabling the model to focus on the most influential keywords.

## Data Sources
EPS Data: Historical Earnings Per Share data for Apple Inc.
Google Trends Data: Time series data for relevant keywords obtained from Google Trends.
Repository Structure
data/: Contains datasets used in the analysis.
notebooks/: Jupyter notebooks for data exploration, model training, and evaluation.
src/: Source code for the Lasso Regression model implementation.
results/: Output files, model checkpoints, and evaluation metrics.

## Usage
Data Collection: Acquire historical EPS data for Apple and relevant keyword data from Google Trends.
Data Preprocessing: Prepare the datasets for training the model.
Model Training: Execute the Lasso Regression model using the provided scripts in the src/ directory.
Evaluation: Assess the model performance and fine-tune if necessary.
Prediction: Use the trained model to nowcast future EPS based on real-time Google Trends data.

## Dependencies
Python 3.x
NumPy
Pandas
Scikit-learn
Jupyter Notebooks (for exploration and visualization)
Acknowledgments
Google Trends for providing valuable data.
Apple Inc. for their financial information.
License
This project is licensed under the MIT License.

## Author
### Richard | drahciR

Feel free to contribute, open issues, or submit pull requests to enhance the model and its predictions.








