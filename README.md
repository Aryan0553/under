# 📊 Decision Tree Depth Analysis & Hyperparameter Tuning

## 🔍 Project Overview
This project demonstrates how the performance of a Decision Tree Classifier varies with tree depth and how GridSearchCV helps in selecting optimal hyperparameters. It clearly explains underfitting, overfitting, and generalization using accuracy curves.


---

## 🧠 Key Concepts
- Synthetic data generation using `make_classification`
- Train–test split evaluation
- Effect of `max_depth` on model complexity
- Bias–variance tradeoff visualization
- Hyperparameter optimization with GridSearchCV

---

## 🛠️ Technologies Used
- Python  
- scikit-learn  
- Matplotlib  
- NumPy  

---

## 📂 Workflow
1. Generate classification dataset  
2. Train Decision Tree with different depths  
3. Compute train and test accuracy  
4. Plot performance curves  
5. Apply GridSearchCV  
6. Evaluate the best model  

---

## 📈 Results
- Training accuracy increases with depth  
- Test accuracy peaks then decreases (overfitting)  
- GridSearchCV improves model generalization  

---

## 📌 Final Performance
- Training Accuracy: ~96.9%  
- Test Accuracy: ~94.6%  

---

## 🚀 How to Run
```bash
pip install scikit-learn matplotlib
python decision_tree_analysis.py
