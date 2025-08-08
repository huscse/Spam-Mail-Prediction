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

# 📊 Classification Report

This report summarizes the performance of the classification model. The model was evaluated on a test set of 15 samples, focusing on its ability to distinguish between "Ham" and "Spam" messages.

---

### Detailed Metrics

| Class | Precision | Recall | F1-Score | Support |
| :--- | :---: | :---: | :---: | :---: |
| **Ham** | 0.64 | 1.00 | 0.78 | 7 |
| **Spam** | 1.00 | 0.50 | 0.67 | 8 |

* **Precision:** The percentage of positive predictions that were actually correct.
* **Recall:** The percentage of actual positives that were correctly identified.
* **F1-Score:** A measure that balances precision and recall.
* **Support:** The number of occurrences of each class in the test set.

---

### Overall Performance

| Metric | Score |
| :--- | :---: |
| **Accuracy** | 0.73 |
| **Macro Average** | 0.72 |
| **Weighted Average** | 0.72 |

* **Accuracy:** The percentage of total predictions that were correct.
* **Macro Average:** The unweighted average of the metrics across all classes.
* **Weighted Average:** The average of the metrics, weighted by the number of samples in each class.

---

## 📌 Future Improvements

- Experiment with advanced models like **Naive Bayes** or **Random Forest**.
- Implement real-time email scanning.
- Create a web-based UI for user interaction.

---

## 🖊️ Author

- Husnain Khaliq 
