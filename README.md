# 📧 Spam Mail Prediction using Logistic Regression

This project predicts whether an incoming email is **Spam** or **Ham** (not spam) using a **Logistic Regression** model.
The workflow includes preprocessing the dataset, splitting into training/testing sets, and training the model for accurate predictions.

---

## 🚀 Workflow

1. **Mail Data**
   Collect email datasets containing labeled examples of spam and ham messages.

2. **Data Preprocessing**

   - Cleaning the text (removing stop words, punctuation, and numbers).
   - Converting text into numerical form using techniques like TF-IDF.
   - Handling missing values.

3. **Train-Test Split**
   Split the processed dataset into **training** and **testing** subsets to evaluate model performance.

4. **Model Training**
   Train a **Logistic Regression** model using the training dataset.

5. **Prediction**

   - Input: New email text.
   - Output: **Spam** or **Ham**.

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:**

  - `pandas` – Data manipulation
  - `numpy` – Numerical computations
  - `scikit-learn` – Machine learning algorithms and preprocessing
  - `matplotlib` / `seaborn` – Visualization

---

## 📊 Model Evaluation

The trained Logistic Regression model is evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

### Model Evaluation Report

          precision    recall  f1-score   support

     Ham       0.64      1.00      0.78         7
    Spam       1.00      0.50      0.67         8

              precision    recall  f1-score   support
accuracy         0.73                            15
macro avg        0.82      0.75      0.72        15
weighted avg     0.83      0.73      0.72        15



---

## 📌 Future Improvements

- Experiment with advanced models like **Naive Bayes** or **Random Forest**.
- Implement real-time email scanning.
- Create a web-based UI for user interaction.

---

## 🖊️ Author

- Husnain Khaliq 
