# Statistical Mechanics of Learning

A professional scientific portfolio implementing concepts from **"Statistical Mechanics of Learning"** by A. Engel & C. Van den Broeck.

Each notebook is a "computational essay" bridging theoretical physics of neural networks with Python implementations.

## 📚 Contents

| # | Notebook | Topic |
|---|----------|---------------|
| 01 | [Polynomial Regression](notebooks/01_polynomial_regression.ipynb) | MLE, bias-variance tradeoff |
| 02 | [Perceptron Basics](notebooks/02_perceptron_basics.ipynb) | Weight evolution |
| 03 | [Perceptron + Noise](notebooks/03_perceptron_noise.ipynb) | Noisy learning, storage capacity $\alpha_c = 2$ |
| 04 | [Annealed Approximation](notebooks/04_annealed_approximation.ipynb) | Annealed Theory and iterative maps $f_1(\varepsilon), f_2(\varepsilon)$ |
| 05 | [Generalization (Quenched)](notebooks/05_generalization_quenched.ipynb) | Quenched Theory, order parameter $R(\alpha)$, $I(R)$ integral |
| 06 | [Learning Rules (1)](notebooks/06_learning_rules.ipynb) | Hebb rule, Perceptron rule |
| 07 | [Learning Rules (2)](notebooks/07_learning_algorithms.ipynb) | Adaline, Pseudo-inverse, Bayesian |

## 🔬 Key Concepts

- **Teacher-Student Scenario**: A student perceptron learns from examples labeled by a teacher
- **Generalization Error** $\varepsilon(\alpha)$: Classification error as function of load $\alpha = P/N$
- **Annealed vs Quenched**: Two approximation schemes for averaging over disorder

## 🚀 Quick Start

```bash
# Clone and setup
git clone https://github.com/lucacristofanill1/statistical-mechanics-and-machine-learning.git
cd statistical-mechanics-and-machine-learning

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# or: venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook notebooks/
```

## 📁 Structure

```
├── notebooks/         # Jupyter notebooks (numbered by topic)
├── src/               # Reusable Python modules
│   ├── theory.py      # Annealed/quenched theoretical functions
│   ├── models.py      # Perceptron implementations
│   ├── simulation.py  # Monte Carlo runners
│   └── plotting.py    # Visualization utilities
├── assets/
│   ├── exercises/     # Original exercise statements (PDF)
│   └── solutions/     # Solved exercise reports (PDF)
└── requirements.txt   # Python dependencies
```

## 📖 Reference

> Engel, A., & Van den Broeck, C. (2001). *Statistical Mechanics of Learning*.  
> Cambridge University Press. ISBN: 9780521774796
