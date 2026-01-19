# Sentiment Analysis on Kaggle sentiment analysis dataset

Authors: Heng YE, Nan LIN, Zhe CHEN

Please refer to the Jupyter Notebook for the detailed implementation and experimental results.

## Prerequisite: Environment Setup

This project uses **Python + `uv`** for dependency management to ensure a fully reproducible environment.

### 1. Install `uv`

If you don’t have `uv` installed:

```bash
pip install uv
```

or (recommended):

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### 2. Create and sync the virtual environment

```bash
uv sync
```

This command will:
- Create a virtual environment (.venv)
- Install exact dependency versions from uv.lock

Do not use `pip install -r requirements.txt`.

This project relies on `pyproject.toml` + `uv.lock` for reproducibility.

### 3. Activate the environment

```bash 
source .venv/bin/activate
```