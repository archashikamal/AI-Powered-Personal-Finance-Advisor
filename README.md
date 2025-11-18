# AI-Powered Personal Finance Advisor

An intelligent system that automatically categorizes expenses, suggests smart investment options, and predicts future savings using machine learning.
Designed for seamless integration into fintech apps, budgeting platforms, or as a standalone automation tool.

## Features

### 1. Expense Categorization
- Classifies transactions into categories like Food, Travel, Bills, Shopping, Investments.
- ML classification based on transaction text and patterns.

### 2. Smart Investment Suggestions
- Recommends SIPs, FDs, index funds, or savings allocations.
- Personalized using spending habits, income, and risk preferences.

### 3. Savings Prediction
- Forecasts monthly and yearly savings.
- Uses regression and time-series forecasting.

## Tech Stack
- Python 3.10+
- Scikit-learn, Pandas, NumPy
- Matplotlib for visualization
- (Optional) FastAPI / Flask for API

## Project Structure
AI-Powered-Personal-Finance-Advisor/
├── data/
│   └── sample_transactions.csv
├── models/
├── notebooks/
├── src/
│   ├── categorizer.py
│   ├── predictor.py
│   └── recommender.py
├── requirements.txt
└── README.md

## How to Run

### 1. Clone repo
git clone https://github.com/yourusername/AI-Powered-Personal-Finance-Advisor.git

### 2. Install dependencies
pip install -r requirements.txt

### 3. Run notebook
jupyter notebook

### 4. Run scripts
python src/categorizer.py
python src/predictor.py

## License
MIT License
