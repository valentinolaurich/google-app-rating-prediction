# Predicting Google Play Store App Ratings

## Project Overview
- This project utilizes Jupyter Notebook to develop a predictive model for estimating app ratings based on various attributes from the Google Play Store dataset.
- It involves data preprocessing, exploratory data analysis, outlier detection, feature engineering, and training a linear regression model. 
- The goal is to help Google identify promising apps for increased visibility in recommendations and search results.

## Features
- Data cleaning and preprocessing
- Handling missing values
- Data type conversion and formatting corrections
- Exploratory data analysis (univariate and bivariate analysis)
- Outlier detection and removal
- Feature engineering
- Model training using linear regression
- Performance evaluation using R-squared metric

## Datasets  
**Dataset:** `googleplaystore.csv`  

### Fields in the dataset:
- **App:** Application name
- **Category:** Category of the app
- **Rating:** Overall user rating
- **Reviews:** Number of user reviews
- **Size:** App size
- **Installs:** Number of downloads
- **Type:** Free or Paid
- **Price:** Cost of the app
- **Content Rating:** Target age group
- **Genres:** Multiple genre classifications
- **Last Updated:** Last update date
- **Current Ver:** Current version
- **Android Ver:** Minimum required Android version

## Key Tasks  
1. **Data Preprocessing**
   - Load data using pandas
   - Identify and handle missing values
   - Convert data types and format inconsistencies
   - Normalize size, reviews, installs, and price fields
   - Remove invalid or inconsistent entries

2. **Exploratory Data Analysis**
   - Perform univariate analysis with boxplots and histograms
   - Identify potential outliers
   - Conduct bivariate analysis to assess relationships between rating and other features

3. **Outlier Treatment**
   - Remove extremely high-priced apps
   - Drop records with unusually high reviews or installs
   - Use percentile thresholds to filter outliers

4. **Feature Engineering**
   - Apply log transformation to skewed numeric variables
   - One-hot encode categorical features
   - Drop non-essential columns

5. **Model Training and Evaluation**
   - Split dataset into training (70%) and testing (30%)
   - Train a linear regression model
   - Evaluate model performance using R-squared score

6. **Prediction and Analysis**
   - Use trained model to predict ratings on test data
   - Assess model accuracy and identify areas for improvement
