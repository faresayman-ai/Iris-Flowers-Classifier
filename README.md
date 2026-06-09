<div align="center">

# 🌸 Iris Flower Classifier
### K-Nearest Neighbors · Scikit-learn · Python

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.x-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

</div>

---

## 📌 Overview

A machine learning project that classifies **Iris flowers** into three species — *Setosa*, *Versicolor*, and *Virginica* — using the **K-Nearest Neighbors (KNN)** algorithm. Built as part of a hands-on ML learning journey.

---

## 🌺 Species Being Classified

| Species | Description |
|---|---|
| 🌸 *Iris Setosa* | Smallest petals, easiest to separate |
| 🌼 *Iris Versicolor* | Medium-sized, overlaps with Virginica |
| 🌺 *Iris Virginica* | Largest petals and sepals |

---

## 📊 Dataset

The classic **Iris Dataset** — one of the most well-known datasets in machine learning.

| Feature | Description |
|---|---|
| `SepalLengthCm` | Length of the sepal in cm |
| `SepalWidthCm` | Width of the sepal in cm |
| `PetalLengthCm` | Length of the petal in cm |
| `PetalWidthCm` | Width of the petal in cm |
| `Species` | Target label (Setosa / Versicolor / Virginica) |

> 150 samples · 3 classes · 50 samples per class

---

## ⚙️ How It Works

```
Raw Data  ──►  Train/Test Split (67% / 33%)  ──►  KNN (k=5)  ──►  Predictions  ──►  Evaluation
```

1. **Load** the Iris CSV dataset using Pandas
2. **Split** the data — 67% training, 33% testing (stratified)
3. **Train** a KNN classifier with k = 5 neighbors
4. **Predict** species on the test set
5. **Evaluate** using precision, recall, and F1-score

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install scikit-learn pandas jupyter
```

### Run the Notebook
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
jupyter notebook Second_project.ipynb
```

> ⚠️ Make sure `Iris.csv` is in the same folder as the notebook, or update the file path inside the notebook.

---

## 📈 Results

The model achieves strong performance across all three species:

```
              precision    recall  f1-score   support

Iris-setosa       1.00      1.00      1.00        17
Iris-versicolor   0.94      0.94      0.94        17
Iris-virginica    0.94      0.94      0.94        16

accuracy                              0.96        50
```

> Accuracy: **~96%** on the test set with k = 5

---

## 🧠 Key Concepts

- **KNN** — a simple, non-parametric algorithm that classifies a point by majority vote of its k nearest neighbors
- **Stratified Split** — ensures each class is equally represented in train and test sets
- **Classification Report** — provides per-class precision, recall, and F1 for a complete picture of model performance

---

## 📁 Project Structure

```
📦 iris-knn-classifier
 ┣ 📓 Second_project.ipynb   # Main notebook
 ┣ 📄 Iris.csv               # Dataset
 ┗ 📄 README.md              # You're here!
```

---

## 🛠️ Built With

- [Python](https://www.python.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [Pandas](https://pandas.pydata.org/)
- [Jupyter Notebook](https://jupyter.org/)

---

<div align="center">

Made with ❤️ as part of a machine learning journey

</div>
