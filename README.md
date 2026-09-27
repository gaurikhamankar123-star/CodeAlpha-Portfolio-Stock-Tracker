# CodeAlpha-Portfolio-Stock-Tracker
# 📈 Stock Portfolio Tracker

A simple **Python-based Stock Portfolio Tracker** that calculates the total investment value based on manually defined stock prices and user-entered quantities.

## 🎯 Objective

Build a basic stock tracker that allows users to enter stock names and quantities, then calculates the total investment using predefined stock prices.

## ✨ Features

* 📊 Manually defined stock prices using a Python dictionary
* ⌨️ User input for stock names and quantities
* 💰 Calculates the total investment value
* ❌ Handles invalid stock names
* 🧮 Performs basic arithmetic calculations
* 💾 Option to save the portfolio result to a `.txt` or `.csv` file

## 🛠️ Technologies Used

* **Python**
* Dictionary
* Input/Output
* Basic Arithmetic
* File Handling *(optional)*

## 📌 Predefined Stock Prices

Example:

```python
stock_prices = {
    "AAPL": 180,
    "TSLA": 250,
    "GOOGL": 150,
    "MSFT": 400,
    "AMZN": 180
}
```

## ▶️ How to Run

1. Clone the repository:

```bash
git clone <your-repository-link>
```

2. Open the project folder:

```bash
cd CodeAlpha-Stock-Portfolio-Tracker
```

3. Run the Python program:

```bash
python stock_tracker.py
```

4. Enter the stock name and quantity when prompted.

## 💡 Example

```text
Available Stocks:
AAPL - $180
TSLA - $250
GOOGL - $150
MSFT - $400
AMZN - $180

Enter stock name: AAPL
Enter quantity: 5

Total Investment: $900
```

## 📂 Project Structure

```text
CodeAlpha-Stock-Portfolio-Tracker/
│
├── stock_tracker.py
├── README.md
└── portfolio.txt   # Optional
```

## 📚 Key Concepts

This project demonstrates:

* Python dictionaries
* User input and output
* Variables and data types
* Conditional statements
* Arithmetic operations
* Basic file handling

