# Password Strength Checker

**Student:** Dhanush

## Project description
This beginner-friendly cybersecurity project checks a sample password against simple rules and provides a strength rating (Weak, Moderate, or Strong) with suggestions for improvement.

## Technologies used
- Python 3
- Jupyter Notebook
- Python standard library (`re`)

## Dataset
No external dataset is required. The project uses a small built-in list of common weak-password examples for demonstration. Do not enter real passwords or share them with others.

## Files
- `Dhanush_PasswordStrengthChecker.ipynb` — complete notebook and code
- `requirements.txt` — dependency list

## Setup and run
1. Install Python 3.
2. Optional: install Jupyter Notebook with `python -m pip install notebook`.
3. Open a terminal in this folder.
4. Run `jupyter notebook`.
5. Open `Dhanush_PasswordStrengthChecker.ipynb`.
6. Run the notebook cells from top to bottom.

The project itself uses only Python's standard library. If Jupyter is already installed, no additional project dependencies are needed.

## Sample output
For `123456`, the program reports **Weak** and advises avoiding common passwords.
For `hello123`, the program reports **Moderate** and lists missing character categories.
For `Sunshine!42`, the program reports **Strong** under this simple rule-based scoring system.

## Limitations and safety
- This is an educational demonstration, not a professional password-auditing tool.
- The checks are simple rules and cannot guarantee that a password is secure.
- Never type a real password that you use for personal accounts into a demonstration project.
