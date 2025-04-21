# pen-digit-classification

https://nbviewer.org/github/omar-ehab04/pen-digit-classification/blob/main/pin_digit.ipynb

for full view


🚀 Digit Classification Project: Pen-Based Handwritten Digits using Machine Learning 🤖✍️

Thrilled to share a recent machine learning project I completed where I built an end-to-end digit classification system using the Pen-Based Recognition of Handwritten Digits dataset . This project dives into supervised classification, dimensionality reduction, model evaluation, and insightful visualizations! 📉📈

🔍 Project Objective
To classify digits (0–9) based on (x, y) pen stroke coordinates collected from digit writing samples. Each instance in the dataset contains 64 features representing sequential pen points, followed by a class label (the digit).

🛠️ Workflow Summary
📦 Data Preprocessing
Loaded dataset using pandas.

Checked for and confirmed no null values.

Verified balanced class distribution — each digit had around 378 samples.

Split the data into training (80%) and testing (20%) using stratified sampling to preserve class balance.

📊 Exploratory Data Analysis
Created a Seaborn count plot to visualize digit distribution — all classes were well-represented.

Applied Principal Component Analysis (PCA) to reduce dimensionality to 2D.

Visualized the PCA output: clear separation between digit clusters ➡️ a strong hint that the data is highly learnable with linear/non-linear models.

🌲 Model Training: Random Forest Classifier
Used Scikit-learn’s RandomForestClassifier with:

n_estimators=100

Default settings for depth, leaf size, etc.

Model trained efficiently with minimal tuning due to the balanced nature and structure of the dataset.

📈 Evaluation Results
Achieved an outstanding accuracy of 95.69% on the test set! ✅

Classification Report Highlights:

Precision: Ranged from 0.93 to 0.99 per class

Recall: Mostly 0.94–0.98, indicating the model captured true positives well

F1-Score: Averaged around 0.95+ for most digits

Model performance was consistent across all digits — no significant bias toward any class.

🧊 Confusion Matrix Insights
Generated a heatmap using Seaborn — most predictions fell along the diagonal (true positives).

Minimal misclassifications, with a few close-digit confusions (e.g., 3 vs. 8) that are expected in handwritten data.

🎨 Visualizations
PCA Plot: Highlighted the power of feature reduction and showed distinct digit groupings.

Count Plot: Ensured no class imbalance that could skew training.

Confusion Matrix Heatmap: Gave a granular look at model accuracy per class.
