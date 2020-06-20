# Binary-Classification-Project

Problem Definition (Binary Classification) - The problem is to predict metal (M) or rock (R) objects from sonar return Dataset. Each pattern is a set of 60 numbers in the range 0.0 to 1.0
Each number represents the energy within a particular frequency band, integrated over a certain period of time.
• Summarize Data – Loaded and analysed data with Descriptive Statistics and Visualizations
• Data Preparation – Cleansed data by imputing missing values. Standardize Data and Feature Selection – used PCA Technique.
• Evaluate Algorithms (Baseline and Standardization) - Created test-harness with 10-fold cross validation to Spot-Check each ML algorithm and MSE metric which measures algorithm performance. Compared ML algorithms to choose the best model using box and whisker plot visually.
• Utilized Pipeline module to automate ML workflows in two use cases.
o Data preparation and modeling
o Feature Extraction (PCA) and modeling
Improve Accuracy - Improved performance of the model using Tuning - Grid Search Parameter technique and Ensemble methods- (Boosting and Bagging Techniques) on standardized dataset.
• Finalize Model - Finalized the model to disk utilizing Pickle API / Joblib API and loaded the model from disk to estimate the performance on unseen data.
