# Breast-Cancer-Prediction
Built a binary classification model using logistic regression to predict whether a tumor is malignant or benign based on diagnostic features. Achieved 97% accuracy on the Breast Cancer Wisconsin dataset. Key steps include data preprocessing, feature scaling, model training, and evaluation using metrics like accuracy, precision.


## 🧠 Breast Cancer Prediction using Logistic Regression

This project focuses on developing a **binary classification model** using **Logistic Regression** to predict whether a tumor is **malignant** or **benign** based on features extracted from breast cancer cell nuclei.

Achieving **97% accuracy**, the model demonstrates strong predictive performance on the **Breast Cancer Wisconsin (Diagnostic) Dataset**.

---

### 📌 Project Highlights

* 📂 **Dataset:** Breast Cancer Wisconsin Diagnostic dataset (from `sklearn.datasets`)
* 🧪 **Target Variable:** Diagnosis (`M = Malignant`, `B = Benign`)
* ⚙️ **Model Used:** Logistic Regression (Supervised ML)
* 📈 **Accuracy Achieved:** 97%
* 📊 **Evaluation Metrics:** Confusion Matrix, Accuracy Score, Precision, Recall, F1-score

---

### 🛠️ Key Steps in the Workflow

1. **Data Loading & Exploration**

   * Checked dataset shape, class distribution, missing values
   * Visualized feature distributions and correlations

2. **Preprocessing**

   * Converted categorical labels to numerical
   * Standardized features using `StandardScaler`

3. **Model Training**

   * Built logistic regression model using `scikit-learn`
   * Used train-test split (e.g., 80-20)

4. **Evaluation**

   * Generated predictions and evaluated using classification report & confusion matrix
   * Plotted decision boundary and ROC curve (optional)

---

### ✅ Key Concepts Learned

* 📌 **Logistic Regression:** Understanding of sigmoid function, log-odds, decision boundary
* 🔍 **Feature Scaling:** Importance of normalization in gradient-based models
* ⚖️ **Evaluation Metrics:** Practical understanding of confusion matrix, precision, recall, F1-score
* 🧪 **Model Validation:** Use of train-test split to assess generalization
* 📊 **Binary Classification:** Real-world application of supervised learning
* 🧼 **Data Preprocessing:** Handling imbalanced classes, encoding, feature standardization

