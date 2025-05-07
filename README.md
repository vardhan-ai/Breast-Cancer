# Breast-Cancer
Data Loading and Exploration:

Loads the dataset using Pandas. Explores the data using descriptive statistics, visualizations (histograms, box plots, correlation matrix), and checks for missing values. Data Preprocessing:

Converts the target variable 'diagnosis' to numerical values (0 for benign, 1 for malignant). Scales numerical features using StandardScaler to ensure features have similar ranges. Splits the data into training and testing sets using train_test_split. Model Training and Evaluation:

Trains three Support Vector Machine (SVM) models: one with a linear kernel, one with an RBF kernel, and an optimized RBF kernel using GridSearchCV to find the best hyperparameters. Evaluates the models using metrics like accuracy, precision, recall, F1-score, and AUC-ROC. Visualization:

Visualizes the decision boundary of the optimized RBF SVM model using a contour plot. Plots ROC curves for all three models to compare their performance.
