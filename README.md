## Roi's Dashboard

An interactive **Streamlit dashboard** demo built with Python.  
The main app (`dashboard.py`) displays a small, Hebrew‑labelled dataset of employees, including:

- **Data table** of employees
- **Bar chart** showing department distribution
- **Average age metric** for employees

There is also a small helper script, `viz.py`, that prints basic visualization‑related messages, and a minimal `dashboardRoi.py` placeholder.

---

## Features

- **Interactive dashboard UI** with Streamlit
- **Random scores** generated with NumPy for demo purposes
- **Pandas DataFrame** for easy data manipulation
- **Visualization** of department counts as a bar chart

---

## Requirements

You need **Python 3.9+** (or similar) and the following Python packages:

- `streamlit`
- `pandas`
- `numpy`

---

## Installation

1. **Clone the repository**

```bash
git clone <YOUR_REPO_URL>.git
cd project10
```

2. **(Optional) Create and activate a virtual environment**

```bash
python -m venv .venv
.\.venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install streamlit pandas numpy
```

---

## How to Run the Dashboard

From the project root, run:

```bash
streamlit run dashboard.py
```

This will open (or show a link to) the Streamlit app in your browser.

---

## Running the Helper Script

To run the simple visualization helper script:

```bash
python viz.py
```

You should see greeting messages printed in the terminal.

---

## Project Structure

- `dashboard.py` – main Streamlit dashboard application  
- `viz.py` – simple script that prints visualization greetings  
- `dashboardRoi.py` – minimal script currently printing "Hello World" (placeholder for future extensions)

---

## License

Add your preferred license here (for example, MIT, Apache 2.0, etc.).

