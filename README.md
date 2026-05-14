# K-nearest-neighbours-project# 🔍 K-Nearest Neighbours Project

A machine learning project implementing the **K-Nearest Neighbours (KNN)** algorithm using Python and Jupyter Notebook. This project works through the full classification pipeline — from exploratory analysis to model optimisation — using a real-world dataset.

---

## 📌 Overview

K-Nearest Neighbours is a simple yet powerful supervised learning algorithm that classifies data points based on the majority class of their `k` closest neighbours in feature space. This project applies KNN to a classification problem and focuses on finding the optimal value of `k` to maximise model performance.

---

## 📁 Repository Structure

```
K-nearest-neighbours-project/
│
├── K Nearest Neighbors Project.ipynb   # Main notebook with full analysis
└── README.md                           # Project documentation
```

---

## 🧪 What's Inside the Notebook

- **Data Loading & Exploration** — Understanding the dataset shape, types, and summary statistics
- **Exploratory Data Analysis (EDA)** — Visualising feature distributions and relationships
- **Data Preprocessing** — Feature scaling using `StandardScaler` (essential for KNN)
- **Model Training** — Fitting a KNN classifier using `scikit-learn`'s `KNeighborsClassifier`
- **Finding Optimal K** — Iterating over a range of `k` values and plotting the error rate to select the best `k`
- **Model Evaluation** — Confusion matrix, classification report (precision, recall, F1-score)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/townspace/K-nearest-neighbours-project.git
   cd K-nearest-neighbours-project
   ```

2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook "K Nearest Neighbors Project.ipynb"
   ```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Jupyter Notebook | Interactive development environment |
| pandas | Data manipulation and analysis |
| NumPy | Numerical computing |
| Matplotlib / Seaborn | Data visualisation |
| scikit-learn | KNN model, scaling, and evaluation |

---

## 📊 Key Concepts

**K-Nearest Neighbours (KNN)** is a non-parametric, instance-based learning algorithm that:
- Stores all training data and makes predictions at query time
- Classifies a point by finding the `k` nearest examples in the training set and taking a majority vote
- Requires **feature scaling** since it relies on distance metrics (e.g. Euclidean distance)
- Has a key hyperparameter `k` — too small causes overfitting, too large causes underfitting

The **elbow method** is used in this project to find the sweet spot for `k` by plotting error rate vs. number of neighbours.

---

## 📬 Contact

Created by [@townspace](https://github.com/townspace) — feel free to raise an issue or get in touch!
