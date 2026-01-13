# Data-Science-Intern

🔹 Iris Flower Classification

The Iris Flower Classification project focuses on predicting the species of an iris flower — Setosa, Versicolor, or Virginica — using sepal and petal measurements. The dataset contains four numerical features: sepal length, sepal width, petal length, and petal width, along with the species label. The problem statement was to build a supervised machine-learning model that can accurately classify the flower species based on these physical characteristics. Initially, I performed data exploration to understand distributions, correlations, and class balance. Since the dataset had no missing values, I mainly focused on visualization, label encoding, and feature analysis.

I trained multiple classification models including Logistic Regression, Decision Tree, Random Forest, SVM, XGBoost, Naive Bayes, and Neural Networks. I evaluated them using accuracy, precision, recall, F1-score, and confusion matrix. When some models showed lower accuracy or overfitting, I applied hyperparameter tuning using GridSearch and RandomizedSearch with cross-validation. I also compared training and testing performance to ensure the model generalized well.

After tuning, Random Forest and XGBoost performed the best, achieving nearly 98% accuracy on test data. This project helped me understand model comparison, tuning techniques, and the importance of choosing evaluation metrics properly. It also showed how clean data and proper visualization can significantly improve model performance.

🔹 Titanic Survival Prediction

The Titanic Survival Prediction project is a binary classification problem that predicts whether a passenger survived the Titanic disaster based on attributes such as age, gender, passenger class, fare, cabin, ticket, and embarkation port. The dataset is a real historical dataset and contains missing values, categorical variables, and noisy patterns. The problem statement was to build a predictive system that could estimate survival probability from passenger information. I started with extensive exploratory data analysis to understand relationships between survival and different features.

To clean the data, I handled missing values using median imputation, removed unnecessary columns, encoded categorical variables using one-hot encoding, and created new meaningful features like cabin groups, ticket types, and passenger titles. Since the initial accuracy was not very high, I applied feature engineering, normalization, and scaling. I then trained multiple models including Logistic Regression, KNN, Decision Tree, Random Forest, SVM, XGBoost, Naive Bayes, and finally an ensemble Voting Classifier.

Initially, single models gave around 75–78% accuracy. To improve performance, I used cross-validation, scaling, and ensemble learning. The Voting Classifier and Random Forest produced the best results with around 80% accuracy. This project taught me how real-world datasets require more preprocessing and how ensemble methods can improve prediction stability.

🔹 Sales Prediction

The Sales Prediction project is a regression problem where the goal is to predict future sales based on advertising and marketing spending data. The dataset contains numerical features such as TV, Radio, and Newspaper advertisement costs along with the Sales target variable. The problem statement was to forecast sales so that businesses can plan marketing strategies and inventory effectively. I began with exploratory data analysis, correlation analysis, and outlier detection to understand feature relationships with sales.

To clean the data, I removed outliers, checked for duplicates, scaled the features using StandardScaler, and removed multicollinearity using VIF analysis. Initially, simple Linear Regression gave lower R² scores. To improve performance, I experimented with multiple regression models including Linear, Lasso, Ridge, Decision Tree, Random Forest, Gradient Boosting, and XGBoost Regressors. I also applied hyperparameter tuning using GridSearch and RandomizedSearch.

Some models showed overfitting with very high training scores, so I removed those and selected models based on test R² performance. The best model was Gradient Boosting / XGBoost Regressor with an R² score close to 0.9, showing strong predictive capability. This project helped me understand regression evaluation, overfitting control, and the importance of model selection based on business relevance.
