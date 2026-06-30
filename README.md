#  Natural Selection for Classifier

##  Overview
This project presents an implementation of a Genetic Algorithm for binary classification, inspired by the principles of natural selection and evolutionary computation. The workflow begins by preprocessing the Wine Dataset and projecting it into a two-dimensional feature space using Principal Component Analysis (PCA). A population of candidate classifiers is then initialized and iteratively improved through fitness evaluation, selection, crossover, and mutation.

The evolutionary process aims to maximize classification accuracy by discovering an optimal decision boundary. Throughout training, the project visualizes the original dataset, the binary classification problem, the evolved classifier, and the progression of fitness across generations. This implementation serves as an educational demonstration of how evolutionary algorithms can be applied to supervised machine learning problems as an alternative to traditional optimization techniques.

---

##  Methodology

1. Load Wine Dataset
2. PCA Projection
3. Genetic Algorithm
4. Evolve Decision Boundary

---

##  Dataset Visualization

The Wine dataset is projected into two dimensions using Principal Component Analysis (PCA) to visualize the separability of the classes.

<p align="center">
  <img src="images/wine_dataset.png" width="700">
</p>

---

##  Binary Classification Dataset

The original three-class dataset is converted into a binary classification problem before applying the evolutionary algorithm.

<p align="center">
  <img src="images/binary_classification.png" width="700">
</p>

---

##  Evolutionary Decision Boundary

After multiple generations, the Genetic Algorithm evolves a classifier capable of separating the two classes.

<p align="center">
  <img src="images/evolved_decision.png" width="700">
</p>

---

##  Evolution of Fitness

The figure below shows how the population improves over successive generations. The best fitness converges quickly, while the average fitness steadily approaches the optimum.

<p align="center">
  <img src="images/evolution_fitness.png" width="700">
</p>

---

##  Features

- Genetic Algorithm from scratch
- PCA visualization
- Binary classification
- Evolutionary optimization
- Fitness-based selection
- Decision boundary visualization

---

## 🛠 Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

##  Getting Started

```bash
git clone https://github.com/sanchit020/natural-selection-for-classifiers.git

cd natural-selection-for-classifiers

pip install numpy pandas matplotlib scikit-learn
```

Run

```bash
jupyter notebook
```

---

##  Repository Structure

```
natural-selection-for-classifiers
│
├── natural-selection-for-classifiers.ipynb
├── README.md
└── images
    ├── wine_dataset.png
    ├── binary_classification.png
    ├── evolved_decision.png
    └── evolution_fitness.png
```

---


---

##  Author

**Sanchit Saini**
