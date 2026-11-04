# Assignment 3 Fashion MNIST Fashion classification


## 🚀 Quick Start

This project uses [uv](https://github.com) for fast, reliable Python dependency management.

### 1. Prerequisites
- **uv** (optional) - [Install uv](https://docs.astral.sh/uv/)

### 2. Setup Environment

Choose **Option A** (recommended for speed) if you have `uv` installed, or **Option B** to use standard Python tools.

#### Option A: Using uv (Fastest)
```bash
# Clone the repository
git clone git@github.com:Elias-Chairi/IE500618-Assignment-3-Fashion-MNIST-Fashion-classification.git && cd IE500618-Assignment-3-Fashion-MNIST-Fashion-classification

# Create venv, lock, and install all dependencies in one step
uv sync
```

#### Option B: Without uv (Standard Python)
```bash
# Clone the repository
git clone git@github.com:Elias-Chairi/IE500618-Assignment-3-Fashion-MNIST-Fashion-classification.git && cd IE500618-Assignment-3-Fashion-MNIST-Fashion-classification

# Create and activate a standard virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate

# Install dependencies from the generated requirements file
pip install -r requirements.txt

# Install JupyterLab manually (since it's not a core project dependency)
pip install jupyterlab
```

### 3. Run the Project

* **If using uv:**
  ```bash
  uv run --with jupyter jupyter lab
  ```
* **If using standard Python (with your activated environment):**
  ```bash
  jupyter lab
  ```

## 📦 Project Structure

```text
├── .python-version/       # Pinned python version
├── notebooks/             # Jupyter notebooks for analysis and prototyping
│   ├── 01_exploration.ipynb
│   └── 02_modeling.ipynb
├── pyproject.toml         # Project metadata and core dependencies
├── uv.lock                # Pinned dependency lockfile
└── README.md              # This file
```

## 🛠️ Main Dependencies

The core toolkit used in this project includes:
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Modeling:** `scikit-learn`

*(Optional: All dependencies and strict versioning are handled automatically inside `pyproject.toml` and `uv.lock`.)*

## 👥 Authors

* **Elias Pettersen Chairi** - [Elias-Chairi](https://github.com/Elias-Chairi)
