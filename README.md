# Iris Flower Classification using SVM  

## 🌸 Overview  
This project applies **Support Vector Machine (SVM)** classifiers to the **Iris dataset** to predict flower species (*setosa, versicolor, virginica*) based on sepal and petal measurements.  
The project compares multiple kernel functions and regularisation parameters, evaluates model performance, and visualises decision boundaries.  

---

## 📊 Dataset  
- **Source:** [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) (built into scikit-learn).  
- **Features:**  
  - Sepal length  
  - Sepal width  
  - Petal length  
  - Petal width  
- **Classes:**  
  - Setosa  
  - Versicolor  
  - Virginica  

---

## ⚙️ Methods  
- Train-test split (**80/20**).  
- Implemented **SVM classifiers** with kernels:  
  - Linear  
  - Polynomial  
  - RBF  
  - Sigmoid  
- Evaluated effect of **regularisation parameter (C)**.  
- Visualised:  
  - Accuracy vs. C (log scale).  
  - Decision boundaries for feature pairs.  

---

## 🚀 Results  
- Accuracy ranges **~95–97%** depending on kernel and hyperparameters.  
- **RBF kernel** performed best overall.  
- Decision boundary plots highlight how different kernels separate the three flower classes.  

---

## 📈 Example Plots  
*(Add images once you run and save your plots)*  

- Accuracy vs Regularisation Parameter (C)  
- Decision boundaries for RBF and Polynomial kernels  

---

## 🛠️ Requirements  
- Python 3.8+  
- Libraries:  
  ```bash
  pip install numpy matplotlib scikit-learn


