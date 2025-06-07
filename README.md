# RSI Prediction using Python 📈

This project demonstrates how to calculate and visualize the **Relative Strength Index (RSI)** for stock price data using Python.

RSI is a popular **momentum oscillator** used in technical analysis to measure the speed and change of price movements. It helps traders identify **overbought** or **oversold** conditions in the market.

---

## 📌 Project Structure

- [`RSI Formula.ipynb`](https://github.com/saranjthilak/RSI-Prediction-using-Python/blob/main/RSI%20Formula.ipynb):  
  Jupyter Notebook containing the Python code to:
  - Import stock price data
  - Calculate RSI step by step
  - Plot RSI against stock price

---

## ⚙️ RSI Formula

The **Relative Strength Index (RSI)** is calculated as:

\[
RSI = 100 - \left( \frac{100}{1 + RS} \right)
\]

Where:  
- **RS** = Average Gain / Average Loss (over N periods)  
- Typical value of N = **14**  

Interpretation:
- RSI > **70** → Overbought
- RSI < **30** → Oversold

---

## 🗂️ Steps in the Notebook

✅ Import required libraries  
✅ Load stock price data (CSV or API source)  
✅ Calculate **daily price changes**  
✅ Calculate **average gain** and **average loss**  
✅ Compute **RS** and then **RSI**  
✅ Plot RSI alongside stock price for easy interpretation  

---

## 📊 Sample Output

![Example RSI Plot](https://upload.wikimedia.org/wikipedia/commons/1/1e/Relative_Strength_Index_example_chart.png)  
![image](https://user-images.githubusercontent.com/94320118/221641372-cde331a3-c273-4757-8154-26a64679926e.png)
![image](https://user-images.githubusercontent.com/94320118/221641493-15dcf9c3-e950-4b04-9a45-6d782d48338a.png)

---

## 🚀 How to Run

1️⃣ Clone the repository:

```bash
git clone https://github.com/saranjthilak/RSI-Prediction-using-Python.git
cd RSI-Prediction-using-Python
