🎬 Movie Rating Classification using Supervised Machine Learning

📌 Project Overview
This project focuses on building a Supervised Machine Learning model to classify movie ratings based on movie characteristics. The dataset contains information such as budget, popularity, runtime, and vote average, which are used as input features to predict whether a movie belongs to a good rating category or not. Before building the models, the data is prepared through feature selection, train-test splitting, and feature scaling to ensure better model performance. Two classification algorithms, K-Nearest Neighbor (KNN) and Decision Tree, are implemented and compared to determine which model provides better prediction results. The project demonstrates how machine learning can be applied to analyze movie data and support rating classification.

🎯 Objectives
Identify the most relevant features for predicting movie ratings.
Prepare the dataset through feature selection, train-test split, and feature scaling.
Build classification models using K-Nearest Neighbor (KNN) and Decision Tree.
Compare the prediction performance of both machine learning algorithms.
Understand how supervised machine learning can be applied to movie analytics.

📊 Key Features Used
Budget
Popularity
Runtime
Vote Average
Movie Rating (Target)

🔍 Key Insights
Most movies in the dataset belong to the good rating category.
Feature scaling improves model performance by ensuring all features have a similar scale.
K-Nearest Neighbor (KNN) achieved better prediction performance than Decision Tree on the dataset.
Both models still have difficulty identifying movies with low ratings because the dataset is dominated by movies with good ratings.
The project shows that selecting appropriate features and algorithms has a significant impact on prediction results.

💡 Recommendations
Perform data cleaning before model training to improve data quality and prediction accuracy.
Consider adding more features such as revenue, profit, genre, or release year to improve model performance.
Apply feature scaling, especially when using distance-based algorithms like KNN.
Optimize model performance through hyperparameter tuning, such as selecting the best value of k for KNN.
Evaluate and compare additional algorithms such as Random Forest, Support Vector Machine (SVM), or Logistic Regression to identify the best-performing model.

🛠 Tools Used
Python
Pandas
NumPy
Scikit-learn
Google Colab
Supervised Machine Learning
K-Nearest Neighbor (KNN)
Decision Tree

📂 Project Deliverables
Machine Learning Notebook (.ipynb)
Movie Analytics Dataset
Data Preprocessing (Feature Selection & Feature Scaling)
KNN Classification Model
Decision Tree Classification Model
Model Evaluation
Project Presentation (Portfolio)

📝 Notes
This project was developed for learning and portfolio purposes to demonstrate the implementation of Supervised Machine Learning in movie analytics. The project compares K-Nearest Neighbor (KNN) and Decision Tree for movie rating classification using selected movie features. Future improvements may include adding more features, handling class imbalance, performing hyperparameter tuning, and evaluating additional machine learning algorithms to achieve better prediction performance.
