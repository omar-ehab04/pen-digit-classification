# pen-digit-classification

https://nbviewer.org/github/omar-ehab04/pen-digit-classification/blob/main/pin_digit.ipynb

for full view

🎯 Project Title: Pen Digits Recognition using Machine Learning

I'm excited to share my machine learning project where I tackled the classic problem of handwritten digit recognition using the Pen Digits dataset. The objective was to develop a model that could accurately classify digits (0–9) based on sequences of 2D pen coordinates—without relying on images!

🚀 Project Highlights:

🔍 Data Exploration & Preparation

Loaded and preprocessed the Pen Digits dataset

Conducted in-depth Exploratory Data Analysis (EDA) using scatterplots and heatmaps to understand data distribution and variable correlations

🧠 Model Selection & Training

Evaluated several classification algorithms including:
✅ Decision Trees
✅ Random Forest (Baseline & Tuned)
✅ Gradient Boosting
✅ XGBoost
✅ Bagging (with SVM & Decision Trees)

Fine-tuned hyperparameters using GridSearchCV for optimal performance

📊 Model Evaluation
Compared performance using accuracy, precision, recall, and F1-score.
✅ Highlights:

Decision Tree: ~86% accuracy

Pruned Decision Tree: ~87%

Gradient Boosting & XGBoost: ~97%

Random Forest: ~97%

Bagging with Decision Trees: ~96%

Bagging with SVM: 💥 99% accuracy — Top performer!
🔬 Feature Engineering & Optimization

Applied PCA, Chi-Square, and Fisher Score to reduce dimensionality

Observed a slight performance improvement with PCA, especially in model efficiency

🧰 Tech Stack:
Python | Scikit-learn | Pandas | NumPy | Seaborn | Matplotlib | XGBoost

📌 Conclusion:
This project was a fantastic opportunity to work through a full ML pipeline — from EDA to model comparison and tuning. It reinforced the value of ensemble methods and feature engineering, with SVM Bagging proving to be the most powerful approach in this case.

📬 Happy to connect with others working on ML, computer vision, or educational AI tools.

#MachineLearning #DataScience #Python #HandwrittenDigitRecognition #PenDigits #ModelTuning #PCA #FeatureSelection #XGBoost #ScikitLearn #EnsembleLearning #DataVisualization #AIProjects
