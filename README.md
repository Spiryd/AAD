# 🧮 AAD

Algorytmiczna Analiza Danych PWr INA 2025/2026

---

This repository contains a collection of Jupyter notebooks for university coursework in data analysis.  
Each notebook demonstrates practical applications of Python data science tools such as pandas, NumPy, etc.

## 📦 Installation Guide

Follow the steps below to set up the project locally.

### 1. Create and activate a virtual environment

**Windows (PowerShell):**
```bash
python -m venv .venv
.venv\Scripts\activate
```

**macOS/Linux:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 2. Install dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 3. Register the environment for Jupyter

```bash
python -m ipykernel install --user --name=.venv --display-name "Python (.venv)"
```

### 4. Launch Jupyter Notebook or JupyterLab

```bash
jupyter notebook
```
or
```bash
jupyter lab
```

---

## 🧠 Recommended VS Code Setup

If you use VS Code:

1. Install the **Python** and **Jupyter** extensions.
2. Open this folder in VS Code.
3. Press `Ctrl + Shift + P` → *Python: Select Interpreter* → choose `.venv`.
4. Open any `.ipynb` file — you should now be able to run cells directly.

---

## 🧰 Dependencies

Main dependencies are listed in `requirements.txt`:

```
jupyter
notebook
numpy
pandas
matplotlib
seaborn
scikit-learn
```

---

## 📄 License

[UNLICENSE](https://unlicense.org) © 2025 Maksymilian Neumann
