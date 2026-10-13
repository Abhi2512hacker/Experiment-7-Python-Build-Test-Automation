# Experiment 7: Automating Build and Testing
[![Build and Test](https://github.com/Abhi2512hacker/Experiment-7-Python-Build-Test-Automation/actions/workflows/ci.yml/badge.svg)](https://github.com/Abhi2512hacker/Experiment-7-Python-Build-Test-Automation/actions/workflows/ci.yml)

## Aim
To automate the build and testing process of a Python application
using GitHub Actions workflows.

## Technologies Used
- Python
- pytest
- Git
- GitHub
- GitHub Actions
- Visual Studio Code

## Project Files
- `calculator.py` - Contains addition and subtraction functions.
- `test_calculator.py` - Contains automated tests.
- `requirements.txt` - Lists the required Python package.
- `.github/workflows/ci.yml` - Defines the build and test workflow.

## How to Run

Install the dependencies:

```bash
py -m pip install -r requirements.txt
```

Run the application:

```bash
py calculator.py
```

Run the tests:

```bash
py -m pytest
```

## Build and Test
The GitHub Actions workflow checks Python syntax and executes
automated tests using Python 3.10 and Python 3.12.

## Result
The Python application's build and testing process is automated
using GitHub Actions.

## Student
Experiment 7 completed using Git, GitHub, Python, pytest, and GitHub Actions.