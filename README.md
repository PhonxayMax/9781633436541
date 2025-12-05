# Runtime 2025-12-05-a

A Jupyter notebook environment for AI engineering and prototyping.

## Setup

### Prerequisites
- Python 3.12+
- uv package manager

### Installation

1. Clone or navigate to this directory:
```bash
cd D:\AI-Engineer\prototyping\runtime-2025-12-05-a
```

2. Create virtual environment:
```bash
uv venv
```

3. Install dependencies:
```bash
uv pip install -r requirements.txt
```

4. Open in VS Code:
```bash
code .
```

## Project Structure

```
runtime-2025-12-05-a/
├── .gitignore          # Git ignore rules (excludes .env, .venv, etc.)
├── .vscode/
│   └── settings.json   # VS Code Python & Jupyter configuration
├── requirements.txt    # Python dependencies
├── index.ipynb         # Main Jupyter notebook
└── README.md          # This file
```

## Dependencies

- **jupyter** - Interactive notebook environment
- **notebook** - Jupyter Notebook interface
- **ipykernel** - Python kernel for Jupyter

## Usage

### Start Jupyter Notebook
```bash
jupyter notebook
```

### Start JupyterLab
```bash
jupyter lab
```

### Run in VS Code
Simply open `index.ipynb` in VS Code with the Jupyter extension installed.

## Environment Protection

The `.gitignore` is configured to protect sensitive information:
- Environment variables (`.env` files)
- Virtual environments (`.venv/`)
- Python cache files
- IDE settings

## VS Code Configuration

The workspace is pre-configured with:
- Python interpreter pointing to `.venv`
- Automatic virtual environment activation
- Jupyter notebook root set to workspace folder
- Hidden clutter files for cleaner workspace
