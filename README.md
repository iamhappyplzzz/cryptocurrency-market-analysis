# Cryptocurrency Market Analysis

A Python notebook project for collecting, cleaning, and exploring cryptocurrency market data from the CoinMarketCap API.

## Project goals

- Retrieve cryptocurrency listings and market data from CoinMarketCap.
- Inspect and clean the dataset with pandas.
- Handle missing values, duplicates, and invalid numeric values.
- Create additional features such as a liquidity ratio and log-transformed variables.
- Explore the data with visualizations using Matplotlib, Seaborn, and Plotly.

## Tools and libraries

- Python
- pandas
- NumPy
- Requests
- Matplotlib
- Seaborn
- Plotly

## Setup

1. Clone or download this repository.
2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Create a CoinMarketCap API key and set it as an environment variable named `CMC_API_KEY`.

   **Windows PowerShell:**
   ```powershell
   $env:CMC_API_KEY="your_api_key_here"
   ```

   **macOS / Linux:**
   ```bash
   export CMC_API_KEY="your_api_key_here"
   ```

4. Open `cryptocurrency_market_analysis.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab and run the cells in order.

## Notes

- API access, rate limits, and available data depend on your CoinMarketCap plan.
- The notebook may create CSV files while collecting and cleaning data. Generated data files are not included in this repository by default.
- Never commit API keys, passwords, or other secrets to GitHub.

## Disclaimer

This project is for educational and analytical purposes only. Cryptocurrency market data is volatile and should not be treated as financial advice.
