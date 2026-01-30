# AI-ML-Internship-Task-10
 KNN – Handwritten Digit Classification
# 🧠 Handwritten Digit Classification using KNN

This project demonstrates **handwritten digit classification** using the **K-Nearest Neighbors (KNN)** algorithm on the **Digits dataset** from Scikit-learn.  
The goal is to classify digits (0–9) by learning patterns from pixel intensity values.

---

## 📌 Project Objectives

- Load and understand the Digits dataset  
- Visualize handwritten digit images  
- Apply preprocessing techniques such as feature scaling  
- Train a KNN classifier  
- Tune the value of **K**  
- Evaluate model performance using accuracy and confusion matrix  
- Visualize predictions on test images  

---

## 📊 Dataset Information

- **Dataset Name:** Digits Dataset (Scikit-learn)  
- **Total Samples:** 1797  
- **Classes:** 10 (Digits 0–9)  
- **Features:** 64 (8×8 grayscale image pixels)  
- **Target:** Digit label (0 to 9)  

---

## ⚙️ Technologies Used

- Python  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

---

## 🚀 Workflow Steps

### 1️⃣ Load Dataset
- Loaded the Digits dataset using `sklearn.datasets.load_digits()`  
- Verified dataset structure by checking shapes of feature matrix **X** and target vector **y**

### 2️⃣ Data Visualization
- Displayed sample digit images using Matplotlib  
- Verified correctness of labels visually  

### 3️⃣ Train-Test Split
- Split data into **80% training** and **20% testing**  
- Used stratified sampling to maintain class balance  

### 4️⃣ Feature Scaling
- Applied `StandardScaler`  
- Scaling is essential because KNN is a **distance-based algorithm**

### 5️⃣ KNN Model Training
- Trained KNN with **K = 3**  
- Evaluated model accuracy on test data  

### 6️⃣ Hyperparameter Tuning
- Tested multiple K values: **3, 5, 7, 9**  
- Stored accuracy for each K  

### 7️⃣ Accuracy vs K Plot
- Plotted accuracy against different K values  
- Identified the best K with highest accuracy  

### 8️⃣ Confusion Matrix
- Generated confusion matrix  
- Analyzed misclassified digits  

### 9️⃣ Prediction Visualization
- Displayed 5 test images along with predicted labels  
- Verified final model output visually  

---

## 📈 Results

- KNN achieved **high accuracy** on the test dataset  
- Best performance observed for optimal K value from tuning  
- Confusion matrix showed strong classification performance across most digits  

---

## 🧪 Sample Output

- Accuracy vs K graph  
- Confusion Matrix visualization  
- Predicted labels on handwritten digit images  

---

