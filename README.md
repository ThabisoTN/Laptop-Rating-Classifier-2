Laptop Rating Classifier 🖥️
A Machine Learning Project to Predict Laptop Ratings (Above/Below)

📌 Overview
This project builds a binary classifier to predict whether a laptop will receive an "Above" or "Below" average rating based on its specifications (e.g., RAM, screen size, brand, weight). The goal is to identify key features influencing laptop ratings and provide actionable insights for product development or purchasing decisions.

🔍 Key Features
Dataset: 1,303 laptops with 12 features (e.g., Company, RAM_GB, Inches, OS) and a target (Rating).

Data Preprocessing: Handled missing values, log-transformed skewed features (e.g., RAM_GB), and removed redundant columns.

Exploratory Data Analysis (EDA): Visualized distributions, detected outliers, and uncovered market trends (e.g., lightweight vs. gaming laptops).

Model Training: Compared Logistic Regression (82% accuracy) and Random Forest (93% accuracy), highlighting the impact of non-linear relationships.

Model Evaluation: Analyzed precision-recall trade-offs, confusion matrices, and class imbalance effects.

🛠️ Tools & Technologies
Python Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn.

Models: Logistic Regression, Random Forest.

Key Techniques: Log transformation, feature engineering, stratified sampling.

🚀 Results
Random Forest outperformed Logistic Regression due to its ability to capture complex feature interactions (e.g., GPU × RAM_GB).

Critical Insights:

Screen size (Inches) and RAM are top predictors of high ratings.

Laptops cluster into two segments: lightweight portables (1.5–2.5 kg) and heavy-duty performers (2.5–4.7 kg).

Class imbalance (51% "Below") subtly biased predictions, emphasizing the need for stratified sampling.



View Project Here https://github.com/ThabisoTN/Laptop-Rating-Classifier-2/blob/main/21930156.ipynb
