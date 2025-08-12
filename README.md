📌 Project: Multilingual Mobile App Reviews Analysis

📄 Overview

This project analyzes multilingual mobile app review data to classify ratings as either positive or negative.
Three different models were used to compare performance: Logistic Regression,and Decision Tree.

---

📂 Dataset

The dataset contains user ratings for mobile apps, review text, review date, and other related metadata.
A new column called *rating\_label* was created, where:

* *1* = Positive review (rating ≥ 3)
* *0* = Negative review (rating < 3)

---

🛠 Process

1. Load the dataset and remove missing values.
2. Prepare the data by dropping unnecessary columns and converting categorical values to numeric.
3. Split the dataset into training, validation, and testing sets.
4. Create a visualization showing the distribution of positive and negative reviews.
5. Train the two models and compare their performance using accuracy,and recall metrics.
6. Test the best-performing model on the final test set.

---

📊 Results

The project achieved good results in classifying reviews, with the Logistic Regression model performing best on the test set.

---

📦 Requirements

* Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn










