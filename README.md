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
- Output: `final_knn.csv` - Preprocessed dataset ready for model training

### Model Development
- `train_models.ipynb`: Implements and evaluates multiple machine learning algorithms and best model is:
  - Gradient Boosting (Accuracy: 76%)

## Key Features
- Complex data integration from 51 interconnected tables
- Advanced data preprocessing and cleaning
- Multiple imputation strategy comparison
- Comprehensive machine learning model evaluation
- Feature importance analysis
- Model performance comparison

## Project Achievements
1. Successfully integrated and preprocessed complex crime data from multiple data tables
2. Implemented and compared multiple imputation strategies for missing data
3. Developed and evaluated 9 different machine learning models
4. Achieved up to 76% accuracy in crime prediction using Gradient Boosting
5. Created a robust data pipeline for crime data analysis

## Data Source
- FBI's National Incident-Based Reporting System (NIBRS)
- Source: https://cde.ucr.cjis.gov/LATEST/webapp/#
- Focus: New Jersey 2022 Crime Data
