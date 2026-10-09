# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

### 1. Install prerequisites

Install Git and Python 3.10 or later. Verify the installations:

```bash
git --version
python --version
```

### 2. Clone the repository

```bash
git clone git@github.com:nhatduyhuynh1-ops/lab01-HuynhNhatDuy.git
cd lab01-HuynhNhatDuy
```

### 3. Create and activate a virtual environment

Windows — Git Bash:

```bash
python -m venv .venv
source .venv/Scripts/activate
```

Windows — PowerShell:

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

Linux/macOS:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 4. Install dependencies

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Run

With the virtual environment activated, start the application:

```bash
python main.py
```

## Test

Run the automated tests:

```bash
python -m pytest
```

## Project structure

```text
lab01-HuynhNhatDuy/
├── .gitignore
├── README.md
├── requirements.txt
├── main.py
└── tests/
```

* `.gitignore` excludes files and directories that should not be tracked, including `.venv/`.
* `README.md` documents setup, execution, and testing.
* `requirements.txt` lists Python dependencies.
* `main.py` is the application entry point.
* `tests/` contains automated tests.

The `.venv/` directory is generated locally and should not be committed to Git.
