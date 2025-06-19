# 📈 Apple Stock Analysis with Python

This project is part of the **IBM Data Analyst Professional Certificate**. It demonstrates how to extract, analyze, and visualize stock data using Python libraries like **YFinance**, **Pandas**, and **Matplotlib**.

---

## 🧠 Objective

- Extract stock price and dividend data using Python
- Analyze long-term trends of Apple Inc. (AAPL)
- Visualize data to uncover insights
- Practice data analysis skills in a real-world context

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- Jupyter Notebook
- [YFinance](https://pypi.org/project/yfinance/)
- Pandas
- Matplotlib

---

## 📊 Project Overview

### 1. Create Ticker Object

```python
import yfinance as yf
apple = yf.Ticker("AAPL")
```

### 2. Get Historical Share Price Data

```python
apple_share_price_data = apple.history(period="max")
```

### 3. Plot Share Opening Price

```python
apple_share_price_data['Open'].plot(title='Apple Opening Share Price')
```

### 4. Get and Plot Dividend Data

```python
apple.dividends.plot(title='Apple Dividends Over Time')
```

---

## 📁 Files

| File Name                    | Description                        |
| ---------------------------- | ---------------------------------- |
| `apple_stock_analysis.ipynb` | Jupyter Notebook with code & plots |
| `apple_stock_analysis.pdf`   | PDF version for easy viewing       |
| `README.md`                  | Project overview and instructions  |

---

## 📌 How to Run

1. **Install Required Packages** (if not already):

   ```bash
   pip install yfinance matplotlib pandas
   ```

2. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook apple_stock_analysis.ipynb
   ```

3. **Run Each Cell** step-by-step to explore data, plots, and insights.

---

## 👤 About the Author

**Thirukkuralan**  
_Aspiring Data Analyst | IBM Certified | Python & SQL Enthusiast_

🔗 [Connect with me on LinkedIn](www.linkedin.com/in/thirukkuralan-data-analyst)  
📂 [Check out more projects in my GitHub Portfolio](https://github.com/Davidkuralan)

---
