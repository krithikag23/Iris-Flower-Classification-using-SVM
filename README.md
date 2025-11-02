# 🌸 Iris Flower Classification using SVM

## 📘 Overview
This project predicts the species of an iris flower (*Setosa*, *Versicolor*, *Virginica*) based on its petal and sepal measurements using a **Support Vector Machine (SVM)** model.  
The Iris dataset is one of the most popular datasets in machine learning and is often used for classification practice and benchmarking algorithms.

---

## 🧠 Workflow
1. **Data Loading:** Import the Iris dataset from `sklearn.datasets`
2. **Exploratory Data Analysis (EDA):** Examine feature relationships and class distributions
3. **Data Preprocessing:** Split the data into training and testing sets, and apply feature scaling
4. **Model Training:** Use an SVM model with an RBF kernel to learn classification boundaries
5. **Evaluation:** Compute accuracy, precision, recall, and F1-score; visualize the confusion matrix
6. **Prediction:** Test model on custom inputs for flower species identification

---

## 📊 Results
- **Accuracy:** 100% (on test data)
- **Precision / Recall / F1-score:** 1.0 for all classes
- The SVM model generalizes extremely well on this balanced dataset.

### 🔍 Example Prediction:
| Sepal Length | Sepal Width | Petal Length | Petal Width | Predicted Species |
|---------------|-------------|---------------|--------------|--------------------|
| 5.1 | 3.5 | 1.4 | 0.2 | Setosa |

---

## 🛠️ Requirements
To install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
