# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

Follow these steps on a fresh machine.

### 1. Install prerequisites

* Install Git.
* Install Python 3.
* Verify the installations:

```bash
git --version
python --version
```

### 2. Clone the repository

```bash
git clone git@github.com:nhatduyhuynh1-ops/lab01-HuynhNhatDuy.git
cd lab01-HuynhNhatDuy
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

**Windows — Git Bash:**

```bash
source .venv/Scripts/activate
```

**Windows — PowerShell:**

```powershell
.venv\Scripts\Activate.ps1
```

**Linux/macOS:**

```bash
source .venv/bin/activate
```

### 5. Install dependencies

If the repository contains `requirements.txt`, run:

```bash
python -m pip install -r requirements.txt
```

If no dependency file exists, install the required packages as specified by the project.

## Run

Activate the virtual environment, then run the application:

```bash
python main.py
```

## Test

Run the automated tests with pytest:

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

* `.gitignore` specifies files and directories Git should ignore, including `.venv/`.
* `README.md` contains setup, run, and test instructions.
* `requirements.txt` lists Python dependencies.
* `main.py` is the application entry point.
* `tests/` contains automated tests.
* `.venv/` is created locally during setup and is not tracked by Git.
