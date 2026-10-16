# Quantum Programming Masterclass with myQLM
## Teratec Forum 2026

Welcome to the **Introduction to Quantum Programming with myQLM** masterclass.

This repository contains all notebooks used during the hands-on session.

The session is designed around practical exercises and guided coding activities. Participants are encouraged to complete the notebooks directly during the workshop.

---

# Prerequisites

To fully participate in the masterclass, participants should have:

- Python 3.10 or newer
- Jupyter Notebook or JupyterLab
- myQLM installed
- (Optional) QuTiP for additional visualisations

---

# Option 1 – Local Installation (Recommended)

## Create a Python Virtual Environment

Using a virtual environment avoids dependency conflicts with existing Python installations.

### Linux / macOS

```bash
python3 -m venv teratec_env

source teratec_env/bin/activate
```

### Windows (PowerShell)

```powershell
python -m venv teratec_env

teratec_env\Scripts\Activate.ps1
```

### Windows (Command Prompt)

```cmd
python -m venv teratec_env

teratec_env\Scripts\activate.bat
```

---

## Install Jupyter and myQLM

```bash
pip install --upgrade pip

pip install jupyterlab myqlm
```

Optional:

```bash
pip install qutip
```

---

# Option 2 – Installation Without a Virtual Environment

If you prefer using your existing Python environment:

```bash
pip install --upgrade pip

pip install jupyterlab myqlm
```

Optional:

```bash
pip install qutip
```

---

# Starting Jupyter

## JupyterLab (Recommended)

```bash
jupyter lab
```

Then open the notebook corresponding to the practical session.

---

# Option 3 – Google Colab

If you do not wish to install myQLM locally, all notebooks can also be executed in Google Colab.

Before starting a notebook, execute:

```python
!pip install myqlm
```

Optional:

```python
!pip install qutip
```

---

# Open the Notebooks in Google Colab

## Lab 1 - Getting started with myQLM

https://colab.research.google.com/github/gregov77/teratec_forum_2026/blob/main/lab1_getting_started_with_myqlm.ipynb

---

## Lab 2 – Bell states and QRoutines

https://colab.research.google.com/github/gregov77/teratec_forum_2026/blob/main/lab2_bell_states_and_qroutines.ipynb

---

## Lab 3 – Full-adder

https://colab.research.google.com/github/gregov77/teratec_forum_2026/blob/main/lab3_full_adder.ipynb

---

## Lab 4 – Quantum teleportation

https://colab.research.google.com/github/gregov77/teratec_forum_2026/blob/main/lab4_quantum_teleportation.ipynb

---

## Lab 5 – Bernstein-Vazirani algorithm

https://colab.research.google.com/github/gregov77/teratec_forum_2026/blob/main/lab5_bernstein_vazirani.ipynb

---

# Additional Resources

## myQLM Documentation

https://myqlm.github.io/
