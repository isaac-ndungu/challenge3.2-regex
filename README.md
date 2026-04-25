# Regex Input Validation & Text Processing

A Python project demonstrating practical applications of regular expressions for input validation, data extraction, and text manipulation — implemented in Jupyter Notebook.


## Overview

This project explores how Python's `re` module can be used to solve real-world text processing challenges. It covers three core regex use cases: validating structured user input, extracting specific patterns from raw text, and performing targeted find-and-replace operations.


## Features

- **Password Validation** — Enforces strong password rules: minimum 8 characters, at least one uppercase letter, one lowercase letter, one digit, and one special character.
- **Date Format Validation** — Checks whether a date string conforms to the `DD/MM/YYYY` format.
- **Email & Phone Extraction** — Scans a block of text and pulls out all valid email addresses and phone numbers matching the `XXX-XXX-XXXX` pattern.
- **Text Replacement** — Demonstrates regex-based substitution, replacing all occurrences of `Mr.` with `Ms.` in a string.


## Prerequisites

Make sure the following are installed on your system before getting started:

- Python 3.8 or higher
- `pip` (Python package manager)
- `git`


## Getting Started

### 1. Clone the Repository

```bash
git clone <repo_link>
cd your-repo-name
```

### 2. Create a Virtual Environment

It is strongly recommended to use a virtual environment to keep dependencies isolated.

**On macOS/Linux:**
```bash
python3 -m venv env
source venv/bin/activate
```

**On Windows:**
```bash
python -m venv env
venv\Scripts\activate
```

You should see `(env)` prefixed in your terminal once the environment is active.

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```


Navigate to the `.ipynb` file and open it to run the cells.

## Usage

Once the notebook is open in Jupyter, run the cells in order from top to bottom. Each section is self-contained:

1. **Password & Date Validation** — Enter input when prompted via `input()` cells to test the validators interactively.
2. **Email & Phone Extraction** — A sample text string is pre-loaded; the notebook will print all matched emails and phone numbers.
3. **Text Substitution** — A sample sentence is processed using `re.sub()` and the result is displayed inline.

To restart and re-run all cells fresh, go to **Kernel → Restart & Run All** in the Jupyter menu.

---

