# Decision Tree Classification & Analysis 

##  Overview
This repository contains a Jupyter Notebook focusing on the implementation, optimization, and interpretation of a **Decision Tree Classifier**. The project covers the full machine learning lifecycle, from handling raw data and conducting Exploratory Data Analysis (EDA) to visualizing the complex decision rules learned by the algorithm.

##  Key Machine Learning Workflows

### 1. Exploratory Data Analysis (EDA) & Data Preparation
* Loaded and inspected the dataset structure using `pandas` and `numpy`.
* Investigated the dataset for missing values, statistical outliers, and inconsistencies.
* Visualized feature distributions and relationships using histograms, box plots, and correlation matrices.

### 2. Feature Engineering
* Prepared the dataset for modeling by applying necessary encoding techniques to categorical variables.
* Scaled numerical features and handled missing values to ensure algorithm compatibility and stability.

### 3. Model Building & Evaluation
* Split the data into an 80/20 train-test split for objective evaluation.
* Implemented a Decision Tree Classification model using `scikit-learn`.
* Evaluated predictive performance using a comprehensive suite of classification metrics:
  * Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

### 4. Hyperparameter Tuning
* Optimized the model's performance and mitigated overfitting through hyperparameter tuning.
* Experimented with critical parameters, including:
  * `criterion` (Gini impurity vs. Entropy)
  * `max_depth` (Pruning the tree to prevent overfitting)
  * `min_samples_split`

### 5. Model Interpretation & Visualization
* Visualized the actual decision tree structure to trace the exact splits and rules learned by the model.
* Analyzed and extracted **Feature Importance** to understand which variables most heavily influenced the model's predictions.

##  Technologies Used
* **Python 3**
* **Jupyter Notebook**
* **Machine Learning:** `scikit-learn`, `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`, `plot_tree` (via sklearn)
