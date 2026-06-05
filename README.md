This project applies the Random Forest ensemble algorithm to predict passenger survival on the Titanic based on historical data. By analyzing demographic and socio-economic factors, I built a classification model to identify the key variables that determined survival outcomes, demonstrating the power of Supervised Learning in solving complex binary classification problems.

Tech Stack & Tools:
1. Key Libraries: pandas, scikit-learn, and seaborn/matplotlib.
2. Methods: RandomizedSearchCV (Hyperparameter Tuning), Feature Engineering, Mean Decrease in Impurity (Feature Importance)

Key Highlights:
1. Data Preprocessing: Managed missing values using robust statistical measures (Median and Mode) and applied encoding to categorical variables to ensure model compatibility
2. Feature Engineering: Developed new predictive features, FamilySize and IsAlone, to capture social dynamics that influenced survival beyond individual attributes
3. Model Optimization: Utilized RandomizedSearchCV with 5-fold cross-validation across 150 iterations to identify the optimal hyperparameters, significantly reducing the risk of overfitting

Performance & Results:
1. Predictive Accuracy: The model achieved a test accuracy of 80% and a weighted average F1-score of 0.80, indicating high reliability in distinguishing between survivors and non-survivors.
2. Feature Importance Insights: Analysis revealed that Sex (0.51) was the most dominant predictor, followed by Pclass (0.15) and Fare (0.12), quantitatively validating the historical "women and children first" evacuation policy
