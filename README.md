# Task 4 – Machine Learning Model Implementation

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SANDHYA KUMARI

*INTERN ID*: CT04DF659

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

---

## 📄 Description

This task focused on implementing a basic **machine learning model** using Python and the **scikit-learn** library. The objective was to choose a suitable classification problem and demonstrate a full workflow including preprocessing, training, prediction, and evaluation.

I selected a **spam detection** task using the publicly available **SMS Spam Collection Dataset**. The task was implemented in a Jupyter Notebook format for better interactivity and documentation. A **Naive Bayes classifier** was used, along with text vectorization to convert messages into numerical data.

## 🧰 Tools & Technologies Used

* **Programming Language:** Python 3.12
* **Libraries Used:**

  * `pandas` – for data loading and manipulation
  * `scikit-learn` – for vectorization, model training, and evaluation
  * `CountVectorizer` – for converting text to feature vectors
* **Dataset:** SMS Spam Collection Dataset (loaded from a public URL)
* **Platform:** Jupyter Notebook (.ipynb)
* **Editor:** Visual Studio Code with Jupyter extension

## 🏗️ Implementation Summary

1. Loaded the dataset containing labeled SMS messages (`ham` or `spam`).
2. Cleaned and prepared the dataset by encoding labels as binary values.
3. Split the data into training and testing sets using `train_test_split()`.
4. Applied `CountVectorizer` to convert raw text into numerical vectors.
5. Trained a `MultinomialNB` (Naive Bayes) classifier using the training data.
6. Evaluated the model using:

   * Accuracy score
   * Classification report (precision, recall, F1-score)

All steps were implemented within a single notebook file for clarity and demonstration purposes.

## 🌍 Real-World Applications

* **Email Filters:** Automatically label emails as spam or not.
* **SMS Gateways:** Filter promotional or phishing texts.
* **Content Moderation:** Detect toxic or unwanted messages.
* **Customer Service:** Categorize incoming queries into topics like support, billing, or complaints.

## ✅ Deliverables

* Jupyter Notebook: `task_4_spam_detection.ipynb`
* No external dependencies beyond common Python libraries and internet access for the dataset

---

This task reinforced essential skills in machine learning workflows: from text preprocessing to model training and evaluation. It showcased how simple yet effective techniques can be used to build predictive models in real-world scenarios.

---


# OUTPUT
<img width="1919" height="1019" alt="Image" src="https://github.com/user-attachments/assets/7142cf10-4a90-4ac1-8115-b712a3110dc6" />
<img width="1919" height="1019" alt="Image" src="https://github.com/user-attachments/assets/c4332629-7a43-41d8-92a1-bc2cfa41af9d" />
