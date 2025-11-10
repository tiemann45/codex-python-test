# Codex Python Test

Professional Python starter that ships with a Jupyter notebook for exploring historical stock prices from Yahoo Finance.

## Project layout

```
├── notebooks/              # Jupyter notebooks (historical_price.ipynb lives here)
├── src/codex_python_test/  # Placeholder Python package for future code
├── pyproject.toml          # Project metadata and dependencies
└── requirements.txt        # Runtime dependency mirror for simple installs
```

## Getting started

### Prerequisites

- Python 3.10+
- `pip` and `venv` (bundled with modern Python)

### Setup

```bash
python -m venv .venv
source .venv/bin/activate            # Windows: .venv\Scripts\activate
pip install --upgrade pip
pip install -r requirements.txt
```

To install optional developer tooling:

```bash
pip install .[dev]
```

### New Section

This is a new section.

### Working with the notebook

1. Start Jupyter Lab (or Notebook):
   ```bash
   jupyter lab
   ```
2. Open `notebooks/historical_price.ipynb`.
3. Enter the ticker symbol plus start and end dates in the provided widgets and run all cells. The notebook fetches dividend/split‑adjusted pricing using `yfinance`, displays a preview, and renders a Matplotlib line chart.

## Testing & linting

Add tests or linters in the `tests/` folder (not yet created). Recommended commands once configured:

```bash
pytest
ruff check .
```

## License

MIT (update as needed).

