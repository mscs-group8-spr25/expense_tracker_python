# Expense Tracker Python

A Python-based expense tracking application. 
**Deployed app can be found here: https://expense-tracker-python-3474.onrender.com/**

## Setup Instructions

### Prerequisites
- Python 3.x installed on your system
- pip (Python package installer)

### Setting up Virtual Environment

1. Open your terminal/command prompt
2. Navigate to the project directory:
```bash
cd expense_tracker_python
```

3. Create a virtual environment:
```bash
# On Windows
python -m venv venv

# On macOS/Linux
python3 -m venv venv
```

4. Activate the virtual environment:
```bash
# On Windows
venv\Scripts\activate

# On macOS/Linux
source venv/bin/activate
```

### Installing Dependencies

With the virtual environment activated, install the required packages:
```bash
pip install -r requirements.txt
```

### Running the Application

1. Make sure your virtual environment is activated
2. Run the application:
```bash
python app.py
```

### Deactivating Virtual Environment

When you're done working on the project, you can deactivate the virtual environment:
```bash
deactivate
```

## Notes
- Always ensure you're working within the virtual environment (you should see `(venv)` in your terminal prompt)
- If you install new packages, update requirements.txt:
```bash
pip freeze > requirements.txt
```
```
