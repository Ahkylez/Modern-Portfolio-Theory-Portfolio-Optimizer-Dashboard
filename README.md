# MPT Optimizer

A streamlit web app for simple portfolio optimization, including backtesting. This was my first finance project and introduced me to many financial math concepts, such as Efficent Frontier, Sharpe Ratio, Feasible set, and other general portfolio management terms. Working through the book "Mathematics for finance" by Marek Capinski and Tomasz Zastawniak, I learned how to impliment math concepts into python and the plethera of libraires that help with it. 
---

## Features

- **Stock Data Integration**  
  - Pulls historical stock price data from Yahoo Finance (`yfinance`).  
  - Flexible ticker input.  

- **Portfolio Optimization**  
  - Minimum Volatility (SD) Portfolio (MVP).  
  - Maximum Sharpe Ratio Portfolio.  
  - Efficient Frontier calculation.  
  - Short-selling toggle for MVP.  

- **Metrics Dashboard**  
  - Annualized return and risk.  
  - Optimal portfolio weights.

- **Visualization**  
  - Portfolio weight comparison (MVP vs Max Sharpe).  
  - Efficient Frontier with simulated portfolios.  
  - Highlighted MVP and Max Sharpe points.  

- **Backtesting**  
  - Out-of-sample performance test (starting at \$1).  
  - Compare MVP and Max Sharpe growth over time against market performance.  
---

## Demo

### Portfolio Metrics
- Annualized return & risk for MVP and Max Sharpe portfolios.  
- Optimal weights displayed in a formatted table.  
### Metrics
![Efficient Frontier Example](screenshots/WebsiteMetrics.png)  

### Efficient Frontier
![Efficient Frontier Example](screenshots/SimulatedPorfolios.png)  

### Backtest
![Backtest Example](screenshots/Backtest.png)  

---

## Libraries

- **Languages**: Python  
- **Libraries**:  
  - `streamlit` – interactive UI  
  - `yfinance` – stock data retrieval  
  - `numpy`, `pandas` – data wrangling & math  
  - `scipy.optimize` – optimization routines  
  - `matplotlib`, `seaborn` – visualization  

---

## Usage
```streamlit run app.py```
