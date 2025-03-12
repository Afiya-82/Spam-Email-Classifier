**📧 Email & SMS Spam Classifier**



🚀 Overview

This project is a Spam Classifier for Emails and SMS messages using Machine Learning and Natural Language Processing (NLP) techniques. It helps in distinguishing between Spam and Ham (Not Spam) messages efficiently.
Dataset

----
**Dataset**
We use a dataset containing labeled SMS and email messages categorized as either "ham" (legitimate) or "spam." The dataset includes features such as message content and metadata.

---
**Exploratory Data Analysis (EDA)**

To better understand the dataset, we conducted an EDA, which includes:

Distribution of Spam vs. Ham Messages:

The dataset is imbalanced, with a higher proportion of ham messages compared to spam messages.

Below is a pie chart representing this distribution:

![Screenshot (124)](https://github.com/user-attachments/assets/1da56992-07b3-419a-99d2-6ac467542bd3)




Character Count Distribution:

Spam messages tend to have a higher character count compared to ham messages.

The histogram below illustrates this distribution:

![Screenshot (125)](https://github.com/user-attachments/assets/58cdfc7c-96b1-47fe-8304-ff259fd179bc)




Word Cloud Analysis:

The most frequent words in spam messages include "free," "call," "win," "txt," and "reply."

Below is a word cloud visualization:

![Screenshot (126)](https://github.com/user-attachments/assets/0e2e3e72-2b4b-4636-a28e-5d4f4691d45f)


---

**Machine Learning Models**

Various machine learning algorithms were trained and tested for classifying messages:

K-Nearest Neighbors (KNN)

Random Forest (RF)

Extra Trees Classifier (ETC)

Logistic Regression (LR)

XGBoost (XGB)

AdaBoost

Gradient Boosting Decision Trees (GBDT)

Decision Tree (DT)

Bernoulli Naive Bayes (BGC)

Support Vector Classifier (SVC)

----

**Model Performance**

To evaluate the models, we used accuracy and precision as the key performance metrics. The bar chart below compares these metrics for different classifiers:

![Screenshot (127)](https://github.com/user-attachments/assets/f5086077-15fe-4a12-83e3-61e3147a4687)

---

🛠️ Tech Stack

Python 🐍

Pandas & NumPy 📊

Matplotlib & Seaborn 📉

NLTK 📝

Scikit-Learn 🤖

-----

📌 Features


✅ Text Preprocessing (Tokenization, Stopword Removal, Stemming)

✅ TF-IDF Vectorization for feature extraction

✅ Multiple ML Models (Logistic Regression, Naive Bayes, Random Forest, etc.)

✅ Accuracy & Precision Comparison

**Made by[Afiya Rani]**
