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

TODO: Add the command to launch the application once the entry-point file is confirmed.

Example:

```bash
python main.py
```

## Test

TODO: Add the project's test command once the testing framework and test files are confirmed.

For a project using pytest:

```bash
python -m pytest
```

## Project structure

```text
lab01-HuynhNhatDuy/
├── .gitignore
├── .venv/                 # Local virtual environment; not tracked by Git
├── README.md
├── requirements.txt       # Project dependencies, if provided
├── main.py                # Application entry point, if applicable
└── tests/                 # Automated tests, if provided
```

The structure above is illustrative. Update it to reflect the actual repository files.
