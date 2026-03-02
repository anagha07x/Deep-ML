# Deep-ML Solutions 🧠
My solutions to problems from [Deep-ML](https://www.deep-ml.com) — a platform for machine learning and math programming challenges.

Solutions are manually uploaded here whenever I solve a problem.

---

## 📁 Structure

```
Deep-ML/
├── Linear_Algebra/
│   ├── easy/
│   ├── medium/
│   └── hard/
├── Deep_Learning/
│   ├── easy/
│   ├── medium/
│   └── hard/
├── Calculus/
│   ├── easy/
│   ├── medium/
│   └── hard/
├── Machine_Learning/
├── Statistics/
├── Data_Preprocessing/
├── Computer_Vision/
├── Information_Theory/
└── ...
```

Each file is named `{id}_{problem_title}.py` (or `.ipynb`) and includes the problem metadata as a header comment.

---

## 📊 Progress

| Category | Easy | Medium | Hard |
|----------|------|--------|------|
| Linear Algebra | - | - | - |
| Deep Learning | - | - | - |
| Calculus | - | - | - |
| Machine Learning | - | - | - |
| Statistics | - | - | - |

---

## 🛠 Tech Stack

- **[Deep-ML](https://www.deep-ml.com)** — problem platform
- **Python / Jupyter Notebooks** — solution format

---

## 📝 Solution Format

Each `.py` file follows this structure:

```python
# Problem 6: Calculate Eigenvalues of a Matrix
# Category: Linear Algebra
# Difficulty: medium
# Source: https://www.deep-ml.com

import numpy as np

def calculate_eigenvalues(matrix: list[list[float]]) -> list[float]:
    eigenvalues = np.linalg.eigvals(matrix)
    return eigenvalues.tolist()
```

---

*Solving consistently. Building intuition.*
