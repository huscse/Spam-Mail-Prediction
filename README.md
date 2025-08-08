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


```
# 📊 Classification Report

This report summarizes the performance of the classification model, specifically detailing its ability to distinguish between "Ham" and "Spam" messages. The model was evaluated on a test set of 15 samples.

---

## Detailed Metrics

| Class | Precision | Recall | F1-Score | Support |
| :--- | :---: | :---: | :---: | :---: |
| **Ham** | 0.64 | 1.00 | 0.78 | 7 |
| **Spam** | 1.00 | 0.50 | 0.67 | 8 |

* **Precision:** The ratio of correctly predicted positive observations to the total predicted positives. For **Spam**, a precision of 1.00 means all messages predicted as spam were, in fact, spam.
* **Recall:** The ratio of correctly predicted positive observations to all observations in the actual class. For **Ham**, a recall of 1.00 means the model correctly identified all actual ham messages.
* **F1-Score:** The weighted average of Precision and Recall. This metric is useful when seeking a balance between precision and recall, especially with uneven class distribution.
* **Support:** The number of actual occurrences of the class in the specified dataset.

---

## Overall Performance

| Metric | Score |
| :--- | :---: |
| **Accuracy** | 0.73 |
| **Macro Average** | 0.72 |
| **Weighted Average** | 0.72 |

* **Accuracy:** The proportion of total predictions that were correct. The model correctly classified 73% of the messages.
* **Macro Average:** The unweighted average of the scores for each class. It treats all classes equally.
* **Weighted Average:** The average of the scores for each class, weighted by the number of samples from that class. This gives a more realistic view of the model's performance on the overall dataset.
```

---

## 📌 Future Improvements

- Experiment with advanced models like **Naive Bayes** or **Random Forest**.
- Implement real-time email scanning.
- Create a web-based UI for user interaction.

---

## 🖊️ Author

- Husnain Khaliq 
