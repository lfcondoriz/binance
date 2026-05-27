# Binance Extractor

A tool for extracting and processing data from the Binance API.

## Description

Binance Extractor is a Python project that simplifies integration with the Binance API to obtain information about markets, prices, and other financial data.

## Requirements

- Python >= 3.11
- `uv` (package manager and virtual environment)

## Installation

### 1. Clone the repository and navigate to the directory

```bash
git clone https://github.com/binance/binance-extractor.git
cd binance-extractor
```

### 2. Create a virtual environment

```bash
uv venv
```

### 3. Activate the virtual environment (optional)

```bash
# On Unix or macOS
`source .venv/bin/activate`

# On Windows
`.venv\Scripts\activate`
```

### 4. Install the package in development mode

```bash
uv pip install -e .
```

## Usage

### CLI (recommended)

```bash
uv run binance
```

### Run as a module (debug / development mode)

```bash
uv run python -m binance
```

### Run as an installed script

```bash
binance
```

## Project Structure

```
binance/
├── src/binance/
│ ├── __main__.py   # Main entry point
│ └── ... # Other modules
├── pyproject.toml  # Project configuration
└── README.md       # This file
```