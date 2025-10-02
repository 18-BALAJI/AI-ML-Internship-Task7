# AI-ML-Internship-Task7: Support Vector Machines (SVM) ⚡📊

## 📖 Description
Day-7 Task of my **AI & ML Internship**: Implementation of **Support Vector Machines (SVM)** for binary classification.  
The project covers linear and non-linear classification using different kernels, decision boundary visualization, and hyperparameter tuning.

---

## 🚀 Objectives
- Load and preprocess dataset (Breast Cancer dataset).  
- Train SVM with **linear kernel**.  
- Train SVM with **RBF kernel**.  
- Visualize decision boundaries in 2D.  
- Tune hyperparameters **C** and **gamma**.  
- Use **cross-validation** for model evaluation.  

---

## 🛠 Tools & Libraries
- Python 3  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📂 Repository Contents
AI-ML-Internship-Task7/
│
├── task7.ipynb # Colab notebook with SVM implementation
├── README.md # Documentation

---

## 📊 Dataset
- **Dataset Used**: [Breast Cancer Dataset (Scikit-learn / Kaggle)](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)  
- Target variable: `0` = Malignant, `1` = Benign  

---

## 🔎 Implementation Workflow
1. Load dataset & preprocess  
2. Train SVM with **linear kernel**  
3. Train SVM with **RBF kernel**  
4. Visualize decision boundary (using 2D features)  
5. Hyperparameter tuning (C, gamma)  
6. Evaluate with accuracy, confusion matrix, and cross-validation  
7. Key observations & interview prep notes  

---

## 📈 Results (Sample)
- **Linear SVM Accuracy**: ~95%  
- **RBF SVM Accuracy**: ~97%  
- Hyperparameter tuning improved boundary separation.  
- Cross-validation shows model generalizes well.  

---

## 📷 Visual Outputs
- Decision boundary plots (Linear vs RBF)  
- Confusion Matrix Heatmap  
- Accuracy comparison across different C & gamma values  

*(Add screenshots after running notebook)*  

---

## 🧾 Key Learnings
- Support Vectors are data points closest to the decision boundary.  
- **C parameter** controls margin hardness (low C = soft margin, high C = hard margin).  
- **Kernels** (linear, polynomial, RBF) allow handling non-linear data.  
- SVMs can be used for both classification & regression (SVR).  
- Overfitting is handled by proper kernel choice & parameter tuning.  

---

## 👨‍💻 Author
**Balaji**  
B.Tech CSE (AI-ML), Parul University  
