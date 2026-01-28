# Statistical Mechanics of Learning

A professional scientific portfolio implementing concepts from **"Statistical Mechanics of Learning"** by A. Engel & C. Van den Broeck.

Each notebook is a "computational essay" bridging theoretical physics of neural networks with Python implementations.

## 📚 Contents

| # | Notebook | Engel Chapter | Topic |
|---|----------|---------------|-------|
| 01 | [Polynomial Regression](notebooks/01_polynomial_regression.ipynb) | Intro | MLE, bias-variance tradeoff |
| 02 | [Perceptron Basics](notebooks/02_perceptron_basics.ipynb) | §2.1-2.2 | Weight evolution |
| 03 | [Perceptron + Noise](notebooks/03_perceptron_noise.ipynb) | §2.3 | Noisy learning, storage capacity $\alpha_c = 2$ |
| 04 | [Annealed Approximation](notebooks/04_annealed_approximation.ipynb) | §2.4 | Iterative maps $f_1(\varepsilon), f_2(\varepsilon)$ |
| 05 | [Generalization (Annealed)](notebooks/05_generalization_annealed.ipynb) | §2.4-2.5 | Order parameter $R(\alpha)$, parametric solver |
| 06 | [Generalization (Quenched)](notebooks/06_generalization_quenched.ipynb) | §2.5 | Quenched theory, $I(R)$ integral |
| 07 | [Learning Algorithms](notebooks/07_learning_algorithms.ipynb) | §2.6-2.8 | Hebb, Adaline, Pseudo-inverse, Bayesian |

## 🔬 Key Concepts

- **Teacher-Student Scenario**: A student perceptron learns from examples labeled by a teacher
- **Generalization Error** $\varepsilon(\alpha)$: Classification error as function of load $\alpha = P/N$
- **Order Parameter** $R = \mathbf{J} \cdot \mathbf{B} / (|\mathbf{J}||\mathbf{B}|)$: Overlap between student and teacher
- **Annealed vs Quenched**: Two approximation schemes for averaging over disorder

## 🚀 Quick Start

```bash
# Clone and setup
git clone https://github.com/YOUR_USERNAME/StatisticalMechanicsMachineLearning.git
cd StatisticalMechanicsMachineLearning

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
├── results/           # Generated plots and outputs
└── requirements.txt   # Python dependencies
```

## 📖 Reference

> Engel, A., & Van den Broeck, C. (2001). *Statistical Mechanics of Learning*.  
> Cambridge University Press. ISBN: 9780521774796

## 👤 Author

**Luca Cristofanilli** - Sapienza Università di Roma