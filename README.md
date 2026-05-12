# Data Handling & Visualization - DHV301

Repository documenting the process of learning data visualization with Python - from environment setup to practicing with pandas, matplotlib, and seaborn.

The assignment focuses on:
- Setting up a Python data analysis environment
- Learning basic Pandas operations
- Exploring and analyzing the Titanic dataset
- Building self-learning and documentation habits

---

# Repository Structure

```text
dataviz-2026/
│
├── setup_test.ipynb
├── setup_log.md
├── pandas_cheatsheet.ipynb
├── titanic_exploration.ipynb
├── learning_log.md
└── README.md
````

---

# File Description

## setup_test.ipynb

Tests importing required libraries:

* pandas
* numpy
* matplotlib
* seaborn

## setup_log.md

Contains setup issues, troubleshooting steps, and references used during environment configuration.

## pandas_cheatsheet.ipynb

Personal Pandas cheat sheet with:

* explanations
* syntax
* self-written examples
* additional functions beyond the required list

## titanic_exploration.ipynb

Titanic dataset exploration and analysis, including:

* initial questions and predictions
* dataset structure analysis
* missing value analysis
* categorical and numerical analysis
* survival rate analysis
* reflections and new questions

## learning_log.md

Learning journal documenting:

* problems encountered
* resources used
* additional concepts learned
* reflections during the assignment

---

# Requirements

Recommended environment:

* Python 3.11
* Anaconda
* VS Code with Jupyter extension

Required libraries:

* pandas
* numpy
* matplotlib
* seaborn
* jupyter

---

# How to Run

## 1. Clone the repository

```bash
git clone <https://github.com/Vasya8386/dataviz-2026>
```

---

## 2. Open the project folder

```bash
cd dataviz-2026
```

---

## 3. Activate the conda environment

```bash
conda activate dataviz
```

---

## 4. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

## 5. Start Jupyter Notebook

```bash
jupyter notebook
```

or open the `.ipynb` files directly in VS Code.

---

# Dataset

The Titanic dataset was loaded using the Seaborn library:

```python
import seaborn as sns

titanic = sns.load_dataset("titanic")
```
