# Assignment 3 Fashion MNIST Fashion classification

Building and comparing simple neural networks by testing hyperparameter variations.
The project uses the [Fashion-MNIST dataset](https://keras.io/api/datasets/fashion_mnist/) containing 28 × 28 grayscale images in 10 clothing categories.

## 🚀 Quick Start

This project uses [uv](https://github.com) for fast, reliable Python dependency management.

### 1. Prerequisites
- **uv** (optional) - [Install uv](https://docs.astral.sh/uv/)
- **Python** (version 3.13) - [Download Python](https://www.python.org/downloads/)

### 2. Setup Environment

Choose **Option A** (recommended) if you have `uv` installed, or **Option B** to use standard Python tools.

#### Option A: Using uv
```bash
# Clone the repository
git clone https://github.com/Elias-Chairi/IE500618-Assignment-3-Fashion-MNIST-Fashion-classification.git
cd IE500618-Assignment-3-Fashion-MNIST-Fashion-classification

# Create the environment and install project dependencies, including JupyterLab
uv sync
```

#### Option B: Without uv
```bash
# Clone the repository
git clone https://github.com/Elias-Chairi/IE500618-Assignment-3-Fashion-MNIST-Fashion-classification.git
cd IE500618-Assignment-3-Fashion-MNIST-Fashion-classification

# Create and activate a standard virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate

# Install dependencies, including JupyterLab and the Python notebook kernel
pip install -r requirements.txt
```

### 3. Run the Project

* **If using uv:**
  ```bash
  uv run jupyter lab
  ```
* **If using standard Python (with your activated environment):**
  ```bash
  jupyter lab
  ```

In the JupyterLab browser tab, open `ASSIGNMENT.ipynb`.

## 📦 Project Structure

```text
├── .python-version   # Pinned Python version (used by uv)
├── ASSIGNMENT.ipynb  # Main Jupyter notebook for the assignment
├── pyproject.toml    # Project metadata and core dependencies
├── requirements.txt  # Dependencies for pip (export of uv dependencies)
├── uv.lock           # Pinned dependency lockfile
└── README.md         # This file
```

## 🛠️ Main Dependencies

The core toolkit used in this project includes:
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `matplotlib`
* **Modeling:** `scikit-learn`, `tensorflow`

## 👥 Authors

* **Elias Pettersen Chairi** - [Elias-Chairi](https://github.com/Elias-Chairi)
