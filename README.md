# Predicting-Hazardous-NEOs-Nearest-Earth-Objects-
a real-world dataset that tracks Nearest Earth Objects (NEOs) observed by NASA from 1910 to 2024.

# Overview
**This project aims to predict whether Nearest Earth Objects (NEOs) are hazardous based on their features. The dataset includes observations of NEOs from NASA, spanning from 1910 to 2024. This dataset provides valuable insights into the characteristics of NEOs and helps in assessing their potential threat to Earth.**

# Dataset
The dataset contains the following features:
*Absolute Magnitude*: A measure of the object's brightness.
*Average Diameter*: The average size of the object.
*Relative Velocity*: The speed of the object relative to Earth.
*Is Hazardous*: The target variable indicating whether the object is hazardous or not.

# Approach

**Import and Clean Data**
Data Import: Load the dataset containing Near-Earth Objects (NEOs) data.
Data Cleaning: Address missing values, remove duplicates, and handle any inconsistencies in the data.

**Exploratory Data Analysis (EDA)**
Data Exploration: Analyze the distribution and summary statistics of the features.
Visualization: Create visualizations to understand relationships between variables and identify patterns.
Correlation Analysis: Investigate correlations between features and the target variable.

**Data Preprocessing:**
Cleaned the dataset by handling missing values and outliers.
Encoded categorical variables and normalized numerical features.

**Feature Selection:**
Identified and selected relevant features that contribute to the prediction of hazardous NEOs.
Model Training and Evaluation:

Applied various machine learning models to classify NEOs as hazardous or non-hazardous.
Evaluated model performance using metrics such as accuracy, precision, recall, and F1-score.

**Best Model Selection:**
Compared the performance of different models and selected the best-performing one based on evaluation metrics.
Key Findings
Data Insights: Key features influencing the hazard classification of NEOs were identified.
Model Performance: The performance of different models varied, with some models outperforming others in terms of accuracy and reliability.
**Best Model**
After evaluating various machine learning models, the *Random Forest* Classifier emerged as the best model for predicting hazardous NEOs. It demonstrated superior performance in terms of accuracy and robustness, making it the most reliable choice for this dataset.

Usage
To use this project:
Clone the repository: git clone https://github.com/yourusername/Predicting-Hazardous-NEOs.git
Install the required packages: pip install -r requirements.txt
Run the Jupyter notebook or Python script to train the model and make predictions.
