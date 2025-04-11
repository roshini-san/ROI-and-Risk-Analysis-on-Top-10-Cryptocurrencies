# ROI-and-Risk-Analysis-on-Top-10-Cryptocurrencies
💸 Top 10 Crypto ROI & Risk Analysis (August 2024)
Analyze historical performance, risk factors, and return on investment for top cryptocurrencies using Python and data visualization.

📝 Description

This project aims to analyze and compare the investment potential of top ten leading cryptocurrencies during August 2024: Bitcoin, Ethereum, Tether, Binance Coin, Solana, USDC, XRP, Cardano, Dogecoin and Toncoin. By performing Exploratory Data Analysis (EDA), Return on Investment (ROI) analysis, and risk assessment on historical OHLC (Open, High, Low, Close) data, this research seeks to identify the optimal investment choices among these cryptocurrencies. The decision-making framework is based on categorizing each cryptocurrency into one of four investment profiles: 
-High ROI-High Risk, 
-High ROI-Low Risk, 
-Low ROI-High Risk 
-and Low ROI-Low Risk. 
These profiles cater to different investor risk appetites and return expectations. The goal is to provide insights that guide investors in selecting cryptocurrencies that align with their investment strategies, whether they seek high returns with higher risks or prefer stable returns with lower risks.

📦 Dependencies
- Python 3.8+
- Google Colab / Jupyter Notebook
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `plotly`

> Install dependencies using:
pip install pandas numpy matplotlib seaborn plotly


📁 Installing & Setting Up

Clone the repository or download the notebook


Open the .ipynb file in Google Colab or Jupyter Notebook.
Run all cells. The notebook includes:
Data cleaning & preprocessing
OHLC visualizations
ROI calculations for 30% & 50% targets
Risk metrics (VaR, CVaR, Sharpe Ratio)
Classification into investment categories

▶️ Executing Program
Step-by-step:
Upload the historical OHLC datasets (CoinMarketCap-based).

Run preprocessing and EDA blocks.

Generate visualizations:
Candlestick charts
Trading volumes
Market capitalization
Cumulative returns

Analyze risk:
Volatility graphs
Correlation matrix
Risk-return classification

📊 Outputs & Visuals
📈 OHLC Candlestick Charts
![Screenshot 2025-04-11 194949](https://github.com/user-attachments/assets/ab8bd850-6792-4fb1-a930-6d5922dcdc8e)
![Screenshot 2025-04-11 195009](https://github.com/user-attachments/assets/55f90980-3f5d-467d-b47b-f8e0a0db37bf)
![Screenshot 2025-04-11 195022](https://github.com/user-attachments/assets/556d5e4a-a355-4573-8e47-c0a702f9b7fc)
![Screenshot 2025-04-11 195029](https://github.com/user-attachments/assets/f114c9d1-f722-4512-a12d-8a43596d825b)

📊 Cumulative Returns Graph
![Screenshot 2025-04-11 195132](https://github.com/user-attachments/assets/7ab49434-c476-474c-b615-7595e79c8099)

🔁 Correlation Matrix
![Screenshot 2025-04-11 195123](https://github.com/user-attachments/assets/24f93c3a-7824-420d-b00a-7f4e4a059bcd)

📉 Volatility Graph
![Screenshot 2025-04-11 195139](https://github.com/user-attachments/assets/afa4b8d6-cb03-42ae-a601-abc392e58ffd)

🧮 ROI-Based Risk Classifier
![Screenshot 2024-10-06 115154](https://github.com/user-attachments/assets/c08b9eac-66ee-4364-8ac8-340b39ad983c)


🛠️ Help
ValueErrors in CSV? → Ensure datetime and numeric formatting is consistent.

🔮 Future Enhancements
Integrate real-time data API (e.g., CoinGecko)
Add Sentiment Analysis using Twitter/Reddit
Deploy as a Streamlit dashboard
Include Monte Carlo simulations for stress testing
Expand to DeFi & altcoins
Risk-adjusted portfolio suggestions
