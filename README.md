# 📊 Evaluation Metrics for Classification Model

This project demonstrates how to evaluate a classification model using advanced performance metrics such as the **Cumulative Accuracy Profile (CAP Curve)**. The CAP curve provides insights into how well the model ranks positive classes, helping to measure discriminatory power beyond basic accuracy.

---

## 📂 Dataset
The dataset used contains labeled data for a binary classification problem. It includes:
- Input features (X)
- Target labels (y)

---

## 🧰 Libraries Used

- Python 3.x
- `numpy`
- `matplotlib`
- `scikit-learn`

---

## ⚙️ Project Workflow

1. Fit a classification model (e.g., Logistic Regression or Decision Tree)
2. Predict probabilities for the test data
3. Sort and calculate CAP values
4. Plot CAP curve and compare against baseline
5. Add:
   - Vertical line at 50% threshold
   - Horizontal line from prediction cutoff

---

## 📸 Screenshot

Below is a sample output showing the final model :

<img src="EvaluationMatrix.png" alt="Evalution Metrics" width="800"/>

---

## ✅ Key Learnings

- How to interpret CAP curve performance
- How to compare prediction power against random guessing
- Visualizing classifier effectiveness

---

## 📃 Requirements

- numpy
- matplotlib
- scikit-learn

---

## 🚀 How to Run

1. Clone the repo or download files
2. Open the Jupyter notebook: `EvaluationMatrix.ipynb`
3. Run all cells step-by-step
