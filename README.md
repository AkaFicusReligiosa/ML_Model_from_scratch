
# Building Machine Learning Models From Scratch

This project focuses on building core machine learning models from scratch without using high-level libraries like Scikit-learn for model implementation. The goal is to understand the mathematical intuition and implement the algorithms using only **NumPy and basic Python**.

---

## 📌 Algorithms Implemented

1. ✅ **Linear Regression**
   - Built using gradient descent and/or normal equation
   - Evaluation metrics: MSE, RMSE, R² Score

2. ✅ **Logistic Regression**
   - Binary classification using sigmoid function
   - Optimization with gradient descent
   - Evaluation metrics: Accuracy, Precision, Recall, F1-score

3. ✅ **SVM Classifier**
   - Support Vector Machine from scratch using hinge loss
   - Implemented with gradient descent
   - Linear kernel only (optional: add polynomial or RBF)

4. ✅ **Lasso Regression**
   - Linear Regression with L1 regularization
   - Coordinate descent / Gradient Descent method
   - Feature selection capability

---

## 🚀 Technologies Used

- Python
- NumPy
- Matplotlib (for visualization)
- Jupyter Notebook

---

## 🧠 Project Structure

```

models-from-scratch/
│
├── LinearRegressionScratch.ipynb
├── LogisticRegressionScratch.ipynb
├── SVMClassifierScratch.ipynb
├── LassoRegressionScratch.ipynb
├── utils/
│   ├── metrics.py      # Common metrics functions
│   └── visualizer.py   # Optional: plotting functions
└── data/
├── linear\_data.csv
├── classification\_data.csv

````

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/models-from-scratch.git
   cd models-from-scratch
````

2. Install dependencies:

   ```bash
   pip install numpy matplotlib
   ```

3. Launch the notebook:

   ```bash
   jupyter notebook LinearRegressionScratch.ipynb
   ```

---

## 🎯 Learning Outcomes

* Gain hands-on experience with loss functions, gradients, and optimization.
* Understand how models work under the hood.
* Explore regularization and margin-based classifiers without abstraction layers.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgements

* Inspired by Andrew Ng’s ML course
* Mathematical insights from ISLR & CS229
* Open-source contributors & Python community

```

  
