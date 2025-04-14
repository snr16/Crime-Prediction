# Crime Data Analysis and Prediction Project

## Project Overview
This project involves comprehensive analysis and predictive modeling of crime data using the FBI's National Incident-Based Reporting System (NIBRS) data, specifically focusing on New Jersey's 2022 crime statistics. The project demonstrates expertise in data preprocessing, feature engineering, and machine learning implementation for crime pattern analysis and prediction.

## Project Structure

### Data Preparation
- `dataset/`: Contains 51 source tables from NIBRS data
- `data_preparation.ipynb`: Implements complex data joining operations to create a unified dataset
- `LAT_LONG.csv`: Contains geospatial data (latitude and longitude) for county-level analysis

### Exploratory Data Analysis (EDA)
- `EDA.ipynb`: Performs comprehensive data analysis including:
  - Null value handling using multiple imputation techniques
  - Feature engineering and visualization
  - Label encoding for categorical variables
- Output: `final_knn.csv` - Preprocessed dataset ready for model training

### Model Development
- `train_models.ipynb`: Implements and evaluates multiple machine learning algorithms:
  - Naive Bayes (Accuracy: 68%)
  - Logistic Regression (Accuracy: 69%)
  - K-Nearest Neighbors (Accuracy: 72%)
  - Support Vector Machine (Accuracy: 71%)
  - Decision Tree (Accuracy: 73%)
  - Random Forest (Accuracy: 75%)
  - AdaBoost (Accuracy: 68%)
  - Gradient Boosting (Accuracy: 76%)
  - Artificial Neural Network

### Imputation Strategy Comparison
- `compare_impute_approach.ipynb`: Compares different null value handling strategies:
  - Drop approach
  - Share-based imputation
  - Weighted imputation
  - KNN imputation

## Key Features
- Complex data integration from 51 interconnected tables
- Advanced data preprocessing and cleaning
- Multiple imputation strategy comparison
- Comprehensive machine learning model evaluation
- Geospatial analysis integration
- Feature importance analysis
- Model performance comparison

## Technical Stack
- Python
- Jupyter Notebooks
- Pandas for data manipulation
- Scikit-learn for machine learning
- TensorFlow for neural networks
- Data visualization libraries
- Geospatial analysis tools

## Project Achievements
1. Successfully integrated and preprocessed complex crime data from multiple sources
2. Implemented and compared multiple imputation strategies for missing data
3. Developed and evaluated 9 different machine learning models
4. Achieved up to 76% accuracy in crime prediction using Gradient Boosting
5. Created a robust data pipeline for crime data analysis

## Data Source
- FBI's National Incident-Based Reporting System (NIBRS)
- Source: https://cde.ucr.cjis.gov/LATEST/webapp/#
- Focus: New Jersey 2022 Crime Data