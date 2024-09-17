# Lagos Flood Prediction Analysis

## Project Overview
This project aims to predict flood events in Lagos, Nigeria using historical weather data and machine learning techniques. The analysis includes data preprocessing, exploratory data analysis, and the development of a predictive model using XGBoost.

## Data Sources
- Kaggle

## Methodology

### 1. Data Preprocessing
- Merged weather data with flood event data
- Handled missing values
- Encoded categorical variables
- Resampled data to monthly frequency

### 2. Exploratory Data Analysis
- Analyzed correlations between features
- Visualized feature distributions and relationships
- Examined the balance of flood vs. non-flood events

### 3. Model Development
- Used XGBoost Classifier for prediction
- Implemented oversampling to address class imbalance
- Split data into training (80%) and testing (20%) sets

### 4. Model Evaluation
- Achieved an accuracy of 94.64% on the test set
- Generated a confusion matrix to visualize model performance

### 5. Feature Importance Analysis
- Identified key features contributing to flood prediction

## Key Findings
- The model outperforms the baseline accuracy of 92.86%
- [Add any specific insights about important features or patterns discovered]

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- imbalanced-learn

## Usage
1. Ensure all dependencies are installed
2. Run the Jupyter notebook 'floods.ipynb' to reproduce the analysis

## Future Work
- Incorporate more recent data as it becomes available
- Experiment with other machine learning algorithms
- Consider adding more features, such as urbanization data or topographical information
