# penguins_ml_proj
Machine learning project analyzing and classifying the Palmer Penguins dataset using Python (KNN, SVM, Logistic Regression)
# Palmer Penguins Species Classification

## Overview
This project applies supervised machine learning techniques to analyze and classify penguin species using physical and categorical features from the Palmer Penguins dataset. The workflow covers data cleaning, exploratory analysis, feature engineering, model training, hyperparameter tuning, and evaluation.

Models implemented include:
- K-Nearest Neighbors (KNN)
- Support Vector Machines (SVM)
- Multinomial Logistic Regression

The project was completed as part of a university-level course and demonstrates an end-to-end applied machine learning pipeline in Python.


## Key Skills Demonstrated
- Data preprocessing and cleaning
- Exploratory data analysis (EDA) and visualization
- Feature engineering and selection
- Supervised machine learning
- Hyperparameter tuning with cross-validation
- Model evaluation using accuracy metrics and confusion matrices


## Dataset
The project uses the Palmer Penguins dataset, which contains biological measurements of penguins from the Palmer Archipelago in Antarctica. Features include bill length, bill depth, flipper length, body mass, island, and sex.


## Data Source

This project uses the Palmer Penguins dataset made available via the
**palmerpenguins** package.

Horst, A. M., Hill, A. P., & Gorman, K. B. (2020).  
*palmerpenguins: Palmer Archipelago (Antarctica) penguin data*.  
R package version 0.1.0.  
https://allisonhorst.github.io/palmerpenguins/  
doi: 10.5281/zenodo.3960218

Data were collected and made available by Dr. Kristen Gorman and the
Palmer Station, Antarctica LTER, a member of the Long Term Ecological
Research Network.

The dataset is released under a **CC-0 license** and is used here for
educational and research purposes.


The dataset is used here for educational and research purposes.


## Methodology

### 1. Data Preprocessing
- Removed observations with missing values
- Encoded categorical variables
- Standardized continuous features where appropriate

### 2. Exploratory Data Analysis
- Visualized distributions of physical measurements
- Examined feature relationships across species
- Identified features most useful for classification

### 3. Feature Selection
- Evaluated subsets of features based on model performance
- Compared results with and without categorical variables

### 4. Modeling
The following models were trained and evaluated:
- K-Nearest Neighbors (KNN) with optimized number of neighbors
- Support Vector Machine (SVM) with tuned kernel parameters
- Multinomial Logistic Regression for multi-class classification

Hyperparameters were selected using cross-validation.

### 5. Evaluation
- Accuracy on held-out test sets
- Confusion matrices to analyze misclassification patterns
- Comparison of model performance across methods


## Results Summary
- KNN achieved approximately 97% accuracy on the test set
- Multinomial Logistic Regression achieved up to 100% accuracy on the test set
- SVM performance was competitive after hyperparameter tuning
- Chinstrap penguins were consistently the most difficult species to classify

