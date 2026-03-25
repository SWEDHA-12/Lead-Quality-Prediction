🚀 Lead Quality Prediction System (FicZon Inc)

📌 Project Overview

In modern sales pipelines, identifying high-quality leads early is critical for improving conversion rates and sales efficiency.
This project focuses on building a machine learning pipeline to classify incoming leads as High Potential or Low Potential, enabling proactive decision-making.

🎯 Problem Statement

FicZon Inc faced challenges in:

* Manually evaluating lead quality
* Delayed sales prioritization
* Reduced conversion efficiency due to reactive decision-making

👉 Goal: Build a **predictive system** to classify lead quality at the top of the funnel.

🧠 Approach

🔹 Data Preprocessing

* Handled missing values and duplicates
* Removed irrelevant and leakage-prone features
* Created meaningful indicators like:

  * `has_mobile`
  * `has_email`

🔹 Feature Engineering

* Extracted time-based features:
  * `hour`
  * `day_of_week`
* Encoded categorical variables
* Derived behavioral and interaction-based insights

🔹 Exploratory Data Analysis (EDA)

Key insights:

* Certain lead sources showed higher conversion probability
* Time-based patterns influenced lead quality
* Missing contact information correlated with lower conversions

🔹 Model Building

Trained and compared multiple models:

* Random Forest
* Gradient Boosting Classifier

📊 Model Performance

| Model               | Accuracy | ROC-AUC |
| ------------------- | -------- | ------- |
| Random Forest       | ~0.72    | ~0.81   |
| Gradient Boosting   | ~0.74    | ~0.80   |

🏆 Final Model

👉 Gradient Boosting Classifier was selected as the final model due to:

* Better handling of non-linear patterns
* Balanced performance across metrics
* Improved generalization on unseen data

⚠️ Key Observation

The model performance plateau (~74% accuracy) is due to:

* Overlapping feature patterns
* Real-world noise in sales behavior
* Similar profiles leading to different outcomes

👉 This reflects a realistic business scenario rather than a model limitation.

💼 Business Impact

* Enables early lead prioritization
* Reduces dependency on manual judgment
* Improves sales team efficiency
Supports data-driven decision making

🛠️ Tech Stack
Python
Pandas, NumPy
Scikit-learn
XGBoost / Gradient Boosting
Matplotlib, Seaborn

📌 Note
Dataset is not included due to confidentiality
This project is a real-world business case simulation

👩‍💻 Author
Swedha Karthikeyan
