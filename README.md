# 🌸 Iris Dataset Flower Classification Using Logistic Regression

This project implements a **Logistic Regression** model to classify Iris flower species based on their morphological features. The dataset used is the classic [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris), which contains 150 samples across three species: *Setosa*, *Versicolor*, and *Virginica*.

---

## 📌 Project Objectives

- Predict the species of Iris flowers using petal and sepal measurements.
- Evaluate the performance of a logistic regression model.
- Analyze precision, recall, F1-score, and accuracy.
- Visualize confusion matrices and interpret model predictions.

---

## 📁 Dataset Description

Each instance in the dataset includes:

| Feature         | Description         |
|-----------------|---------------------|
| `sepal_length`  | Length of sepal (cm)|
| `sepal_width`   | Width of sepal (cm) |
| `petal_length`  | Length of petal (cm)|
| `petal_width`   | Width of petal (cm) |
| `species`       | Target class         |

---

## 🔧 Tools & Libraries Used

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (`LogisticRegression`, `LabelEncoder`, metrics, model selection)

---

## ⚙️ Workflow

1. **Data Preprocessing**
   - Loaded the dataset and encoded the target labels using `LabelEncoder`.

2. **Model Training**
   - Trained a logistic regression model using scikit-learn.

3. **Evaluation**
   - Used confusion matrices and classification reports to assess performance.
   - Applied 10-fold cross-validation to validate model stability.

4. **Interpretation**
   - Precision, recall, and F1-scores were calculated for each class.
   - Class 0 achieved perfect scores; class 1 and 2 showed strong but slightly lower performance.

---

## 📈 Model Results Summary

- **Accuracy**: 93%
- **Class 0**: Perfect classification (Precision, Recall, F1-score = 1.00)
- **Class 1**: Precision = 1.00, Recall = 0.85, F1-score = 0.92
- **Class 2**: Precision = 0.75, Recall = 1.00, F1-score = 0.86

---

## ✅ Conclusion

The logistic regression model demonstrated high accuracy and strong classification performance on the Iris dataset. With simple preprocessing and minimal tuning, it effectively differentiated between the three flower species using only four input features.

---

