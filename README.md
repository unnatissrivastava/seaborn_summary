# 📊 Seaborn Cheat Sheet

A quick, beginner-friendly **Seaborn Cheat Sheet** covering the most commonly used plots, functions, and customization options for data visualization in Python.

This repo is meant as a handy reference whether you're learning Seaborn for the first time or just need a quick reminder of syntax while working on a data science project.

---

## 📄 Contents

- [`seaborn_cheatsheet.pdf`](./seaborn_cheatsheet.pdf) — the main cheat sheet document

---

## 📚 Topics Covered

- Seaborn Basics
- Built-in Datasets
- Statistical Plots
- Distribution Plots
- Categorical Plots
- Matrix Plots
- Regression Plots
- Themes & Styles
- Color Palettes
- Figure Customization

---

## 🛠️ Tech Stack

- Python
- Seaborn
- Matplotlib
- Pandas
- NumPy

---

## 🚀 Getting Started

If you want to follow along or try out the examples yourself:

```bash
pip install seaborn matplotlib pandas numpy
```

Then in Python:

```python
import seaborn as sns
import matplotlib.pyplot as plt

# Load a built-in dataset
df = sns.load_dataset("tips")

# Example plot
sns.scatterplot(data=df, x="total_bill", y="tip", hue="sex")
plt.show()
```

---

## 🤝 Contributing

Suggestions and improvements are welcome! Feel free to open an issue or submit a pull request if you'd like to add more examples or fix something.

---

## ⭐ Support

If you found this cheat sheet useful, consider giving this repository a **Star ⭐** — it helps others find it too.
