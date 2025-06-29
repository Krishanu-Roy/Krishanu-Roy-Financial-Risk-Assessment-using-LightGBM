# Financial Risk Assessment using LightGBM

## Overview

This project leverages machine learning to assess financial risk preferences (Low, Medium, High) based on personal income and expense data. Using the LightGBM algorithm, the model predicts a user's risk category, which can be useful for financial institutions, credit scoring, or personal finance management. An interactive dashboard is built with Streamlit for real-time predictions and data visualization.

---

## Features

- **Data Preprocessing:** Automated cleaning and feature engineering of income and expense data.
- **Modeling:** LightGBM classifier for high-performance risk prediction.
- **Dashboard:** Streamlit app for user-friendly, real-time risk assessment and visualization.
- **Reproducibility:** All code and data are organized for easy experimentation and extension.

---

## Tech Stack

- **Python 3.11+**
- **pandas, numpy** (data manipulation)
- **LightGBM** (machine learning)
- **scikit-learn** (model evaluation)
- **Streamlit** (web dashboard)
- **Git** (version control)

---

## Dataset

The dataset (`data/financial_data.csv`) contains the following columns:
- `Income`: User's annual income
- `Expenses`: User's annual expenses
- `Risk Preference`: Target variable (`Low`, `Medium`, `High`)

---

## Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/Krishanu-Roy/Financial-Risk-Assessment-using-LightGBM.git
cd Financial-Risk-Assessment-using-LightGBM
```

### 2. Set Up the Environment

It is recommended to use Python 3.11 or compatible.

```sh
python -m venv venv
venv\Scripts\activate  # On Windows
# source venv/bin/activate  # On Linux/Mac
pip install -r requirements.txt
```

### 3. Run the Streamlit App

```sh
streamlit run streamlit_app.py
```

---

## Usage

- Open the Streamlit app in your browser.
- Input income and expense values to get a real-time risk prediction.
- Explore data visualizations and model insights.

---

## Project Structure

```
Financial-Risk-Assessment-using-LightGBM/
│
├── data/
│   └── financial_data.csv
├── streamlit_app.py
├── model.py
├── requirements.txt
└── README.md
```

---

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## Author

[Krishanu Roy](https://github.com/Krishanu-Roy)
