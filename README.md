
# Project Setup Guide

This guide provides step-by-step instructions to set up your project environment, including how to configure a Python virtual environment using Pipenv, pip, or Conda.

## Table of Contents

1. [Setting Up a Python Virtual Environment](#setting-up-a-python-virtual-environment)  
   - [Using Pipenv](#using-pipenv)  
   - [Using pip and venv](#using-pip-and-venv)  
   - [Using Conda](#using-conda)  
2. [Running the Application](#running-the-application)

## Setting Up a Python Virtual Environment

### Using Pipenv
1. **Install Pipenv (if not already installed):**
   ```
   pip install pipenv
   ```

2. **Install Project Dependencies:**
   ```
   pipenv install
   ```

3. **Activate the Virtual Environment:**
   ```
   pipenv shell
   ```

---

### Using `pip` and `venv`
1. **Create a Virtual Environment:**
   ```
   python -m venv venv
   ```

2. **Activate the Virtual Environment:**  
   **macOS/Linux:**
   ```
   source venv/bin/activate
   ```  
   **Windows:**
   ```
   venv\Scripts\activate
   ```

3. **Install Project Dependencies:**
   ```
   pip install -r requirements.txt
   ```

---

### Using Conda
1. **Create a Conda Environment:**
   ```
   conda create --name myenv python=3.11
   ```

2. **Activate the Conda Environment:**
   ```
   conda activate myenv
   ```

3. **Install Project Dependencies:**
   ```
   pip install -r requirements.txt
   ```

---

# Running the Application

## Phase 1: Create the AI Agent
```
python AI_agent.py
```

## Phase 2: Set Up the Backend with FastAPI
```
python backend.py
```

## Phase 3: Launch the Frontend with Streamlit
```
python frontend.py
```

---

# Important Note
Make sure the backend script (`backend.py`) is running in a separate terminal window before starting the frontend.

