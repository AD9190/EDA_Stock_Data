# "Insights into Financial Markets: A Comprehensive Analysis of Bank Stock Data"

## Overview
This project focuses on exploring the historical stock prices of bank stocks, specifically looking at their progression from the financial crisis to early 2024. It is important to note that this analysis is **not meant to be a robust financial analysis or financial advice** but rather an exercise in data exploration.

## Project Structure
- **`EDA_Stock_Data.ipynb`**: Jupyter notebook containing the code for the EDA.
- **`README.md`**: This file, providing an overview of the project.

## Libraries Used
- `pandas_datareader.data`: For fetching historical stock data.
- `yfinance`: Another library for fetching stock data.
- `pandas`: Data manipulation and analysis.
- `matplotlib`, `seaborn`, `plotly`: For data visualization.
- `cufflinks`: Provides interactive plots for Pandas.
- `pandas_ta`: For technical analysis indicators.

## Setup Instructions
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/AD9190/EDA_Stock_Data.git
2. **Install Dependencies**
   ```bash
   pip install pandas pandas_datareader yfinance matplotlib seaborn plotly cufflinks pandas_ta
3. **Run the notebook**
   Open EDA_Stock_Data.ipynb in Jupyter or any compatible notebook environment.
   Execute the cells to run the analysis.
 ## Data Collection
   The historical stock data for bank stocks was fetched using pandas_datareader and yfinance.
   Tickers used: JPM (JPMorgan Chase & Co.), GS (Goldman Sachs Group Inc.), BAC (Bank of America Corporation), C (Citigroup Inc.).
   Date range: From the early 2000s to early 2024.
## Analysis Highlights
   **Basic Statistics:** Summary statistics of stock prices.
   **Time Series Visualization:** Plots of stock prices over time.
   **Candlestick Charts:** Visualizing open, high, low, close prices.
   **Financial Crisis Analysis:** Highlighting the period and comparing stock performance.
   **Returns Analysis:** Calculating and visualizing returns.
## Usage
  Open notebook.ipynb in Jupyter or any compatible notebook environment.
  Run the cells to execute the analysis.
  Feel free to modify the notebook or add more analysis as needed.
## Notes
  This project is solely for educational and exploratory purposes.
  Any financial decisions should not be based on this analysis alone.
  For any questions or issues, feel free to contact [adasgupta2004@gmail.com].


