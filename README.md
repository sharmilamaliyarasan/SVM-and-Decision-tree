# 🎯 Multi-Class SVM Classification Project

## 📖 Description

This project demonstrates Support Vector Machine (SVM) for multi-class classification using Python.

The notebook svm_multi.ipynb covers:

Data loading and exploration

Training SVM on a multi-class dataset

Performance evaluation

Visualization of decision regions

## 📂 Dataset

File: svm_multi.csv

Features: x1, x2

Target: class (3 categories)

Size: ~300 rows (synthetic dataset)

## ⚙️ Methods

Load dataset using Pandas

Train SVC (scikit-learn) with linear and RBF kernels

Apply One-vs-One (OvO) strategy (default in SVC)

Evaluate model performance using accuracy score

Plot decision regions with Matplotlib

## 📊 Results

✅ SVM successfully classified all 3 classes with high accuracy

✅ Decision region plots clearly show class boundaries

✅ RBF kernel handled non-linear separations better than linear

## 📦 Requirements

Install dependencies with:

pip install pandas numpy matplotlib scikit-learn

Open Jupyter Notebook:

jupyter notebook svm_multi.ipynb


Run all cells to reproduce results.

## 📈 Conclusion

SVM with OvO strategy is effective for multi-class classification

Kernel choice matters: Linear is simple, but RBF performs better when data is not linearly separable

Visualization confirms clear separation between the 3 classes

## 🚀 Future Improvements

🔹 Try polynomial kernel for more complex decision boundaries

🔹 Perform GridSearchCV for hyperparameter tuning (C, gamma)

🔹 Test on real-world datasets (e.g., Iris dataset)
