# Python Project Setup Guide

Welcome! Follow the steps below to set up your development environment and install the project dependencies.

##  Getting Started

### Clone Repository:
https://github.com/Damiemmy/bincom_first_contact_session.git

### 1. Create a Virtual Environment

A virtual environment keeps this project's dependencies separate from other Python projects.

python -m venv venv

### 2. Activate the Virtual Environment

**Windows (Command Prompt):**

venv\Scripts\activate


### 3. Install Project Dependencies

Install all the packages listed in `requirements.txt`:
run: python -m pip install -r requirements.txt


### 4. Verify Installed Packages

To see the packages installed in your virtual environment, run:

```bash
python -m pip list
```

### 5. Deactivate the Virtual Environment

When you're done working on the project, run:

run: deactivate

## Important Notes

- Ensure Python is installed on your machine.
- Activate your virtual environment before installing or running project dependencies.
- Make sure `requirements.txt` is located in your project root directory.
- Keep your virtual environment (`venv/`) out of Git using `.gitignore`.

**Happy Coding!** 💻