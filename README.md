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

## 📸 Output Example

### CAP Curve
![CAP Curve](images/cap_curve.png)

### Cumulative Accuracy Profile
![Cumulative Accuracy Profile](images/cumulative_accuracy.png)

---

## ✅ Key Learnings

- How to interpret CAP curve performance
- How to compare prediction power against random guessing
- Visualizing classifier effectiveness

---

## 📃 Requirements

Create a `requirements.txt` file:

```txt
numpy
matplotlib
scikit-learn
