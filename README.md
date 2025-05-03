
# 📘 Support Vector Machine (SVM) Exploration Project

This project demonstrates the power and flexibility of **Support Vector Machines (SVM)** in supervised classification tasks using both real-world and synthetic datasets. It covers data preprocessing, model training, kernel visualization, and hyperparameter tuning with a technical and structured approach.

---

## 📌 Objectives

1. **Train an SVM model** to classify human cell samples as benign or malignant using `cell_samples.csv`.
2. **Visualize kernel functionality** to understand the mathematical intuition behind non-linear SVMs.
3. **Evaluate and tune SVM models** using the classic Iris dataset with different kernels and hyperparameters.

---

## 🗃️ Dataset Requirements

| Task | Dataset | Source |
|------|---------|--------|
| Task 1 | `cell_samples.csv` | Provided locally (`./SVM/cell_samples.csv`) |
| Task 2 | Synthetic (moons) | `sklearn.datasets.make_moons` |
| Task 3 | IRIS dataset | `sklearn.datasets.load_iris` |

---

## ⚙️ Project Structure

```
├── SVM_Classifier.ipynb      # Jupyter notebook with all 3 tasks
├── cell_samples.csv          # Dataset for Task 1 (must be placed manually)
├── README.md                 # Project documentation
```

---

## 📊 Breakdown of Tasks

### ✅ Task 1: Classify Human Cell Samples
- Loads `cell_samples.csv`
- Cleans data and selects features
- Trains a **Linear SVM**
- Outputs a **classification report** on test data

### ✅ Task 2: Visual Intuition of Kernels
- Uses synthetic "moons" dataset
- Trains an SVM with **RBF kernel**
- Plots decision boundary to visualize non-linear separation

### ✅ Task 3: Iris Dataset Classification
- Loads built-in IRIS dataset
- Compares **linear vs RBF kernels**
- Performs **GridSearchCV** to find optimal `C` and `gamma`
- Reports best accuracy and parameters

---

## 🚀 Getting Started

1. Clone the repo or download the `.ipynb` and `cell_samples.csv` files.
2. Ensure dependencies are installed:
   ```bash
   pip install numpy pandas matplotlib scikit-learn
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook SVM_Classifier.ipynb
   ```
4. Run each cell sequentially to observe outputs and insights.

---

## 🧠 Key Learnings

- SVMs can be highly effective in both **linear** and **non-linear** classification.
- **Kernels** allow SVMs to transform feature spaces for better decision boundaries.
- **Grid search tuning** significantly improves model performance.

---

## 📩 Contact

For questions, suggestions, or collaborations:  
**Sarthak** – AI & DS Engineer | ML Enthusiast
