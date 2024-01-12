# Breast Cancer Diagnosis: Exploratory Data Analysis

This project performs an exploratory data analysis on a dataset of features extracted from digitized images of breast mass tissue to classify tumors as benign or malignant.

## Dataset

The dataset contains 569 data points with 33 feature measurements each related to characteristics of the cell nuclei present in the image.

Features include:

- Mean, standard error and worst values for metrics like radius, texture, smoothness etc.  
- Diagnosis outcome variable with benign (357 observations) and malignant (212 observations) classes

## Analysis 

The analysis covers:

- Data loading, inspection and preprocessing
- Summary statistics and distributions of features
- Correlation analysis using heatmaps
- Data visualization using plots like jointplots, violin plots, swarm plots etc.
- Feature engineering and standardization 
- Comparing models like Random Forest, XGBoost, Decision Trees using accuracy metrics
- Tuning hyperparameters like tree depth and criterion 
- Validation using k-Fold cross validation

Key libraries used include Pandas, Matplotlib, Seaborn, Scikit-Learn etc.

## Insights

- Radial metrics have high correlation to diagnosis
- Random Forest model provides 96% accuracy
- Optimal tree depth is around 3 for decision trees

The analysis provides a blueprint for applying machine learning to medical diagnosis based on imaging data. Models can further be improved by techniques like hyperparameter tuning.
