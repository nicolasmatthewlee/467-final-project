# 467-final-project

## Setup

Requires Python 3.12.2

### 1. Create and activate a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Register the Jupyter kernel

```bash
python -m ipykernel install --user --name denoising --display-name "Python (Denoising)"
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Select **Kernel → Change Kernel → Python (Denoising)**.

### 5. Update dependencies when needed

```bash
pip install -r requirements.txt
```
