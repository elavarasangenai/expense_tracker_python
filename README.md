# Expense Tracker

Track your expense by categorywise you spend.

---

![Expense Tracker Demo]({URL or path to demo asset})

---

## Table of Contents
- [About](#about)
- [Features](#features)
- [Demo](#demo)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

---

## About
**Expense Tracker** helps you manage and track your expenses by category. It was created to solve the problem of maintaining expenses in a categorywise manner.

## Features
- Manage Category
- Manage Expense
- Graphical view by category

## Prerequisites
- Python 3.8+
- [streamlit](https://streamlit.io/)
- [pandas](https://pandas.pydata.org/)
- [requests](https://requests.readthedocs.io/)

---

## Installation
```bash
# Clone the repository
git clone https://github.com/elavarasangenai/expense_tracker_python.git
cd expense_tracker_python

# (Optional) Create and activate a virtual environment
python -m venv env
.\env\Scripts\activate  # On Windows
# source env/bin/activate  # On Linux/Mac

# Install dependencies
pip install streamlit pandas requests
```

---

## Usage
```bash
# Run the Streamlit app
streamlit run frontend/app.py

# (If you have a backend)
python backend/app.py
```

---

## Configuration
- You can set environment variables as needed for backend API URLs, database paths, etc.
- Example:
```bash
set BACKEND_URL=http://localhost:5000  # On Windows
# export BACKEND_URL=http://localhost:5000  # On Linux/Mac
```
- Edit configuration in `frontend/app.py` or `backend/app.py` as required.

---

## Roadmap
- Memberwise Expense Tracker
- Weekly and Monthly Report


---

## License
{e.g. MIT, Apache-2.0}

---

## Author
{Elavarasan}

---

## Acknowledgements
- Special thanks to open-source libraries: Streamlit, Pandas, Requests