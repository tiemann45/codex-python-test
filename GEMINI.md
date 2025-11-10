# Project Overview

This project is a Python-based tool for exploring historical stock prices. It uses `yfinance` to fetch dividend and split-adjusted pricing data from Yahoo Finance. The main functionality is within a Jupyter notebook (`notebooks/historical_price.ipynb`) that allows users to interactively query and visualize stock data using `ipywidgets` and `matplotlib`.

The project is structured as a professional Python project, with dependencies managed by `pip` and project metadata defined in `pyproject.toml`.

# Building and Running

### Prerequisites

- Python 3.10+
- `pip` and `venv`

### Setup & Running

1.  **Create and activate a virtual environment:**
    ```bash
    python -m venv .venv
    source .venv/bin/activate
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Start Jupyter Lab:**
    ```bash
    jupyter lab
    ```

4.  **Use the notebook:**
    Open `notebooks/historical_price.ipynb` and interact with the widgets to fetch and visualize stock data.

# Development Conventions

## Testing and Linting

The `README.md` suggests using `pytest` for testing and `ruff` for linting. The project is configured to install these tools with:

```bash
pip install .[dev]
```

However, no tests or configuration files for these tools are present in the project yet.

## Project Structure

-   `notebooks/`: Contains Jupyter notebooks for data exploration.
-   `src/codex_python_test/`: A placeholder for the project's Python source code.
-   `pyproject.toml`: Defines project metadata and dependencies.
-   `requirements.txt`: A mirror of the project's dependencies for easy installation.
