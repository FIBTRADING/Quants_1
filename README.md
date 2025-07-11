# Quants_1
📈 Financial Modeling with Python

This repository provides Python implementations of fundamental models in finance and portfolio optimization, including:

    Capital Asset Pricing Model (CAPM)

    Continuous Coupon Bond Pricing

    Markowitz Modern Portfolio Theory (MPT)

    Sharpe Ratio-based Portfolio Optimization (US and India Markets)

Each script demonstrates a specific model with real-time or historical data from financial APIs like yfinance and nsepy.
📂 Contents
File	Description
CAPM.py	Implements CAPM to estimate beta and expected return for a stock.
continuousBondPricing.py	Prices a continuous coupon bond using exponential discounting.
MarkowitzModel.py	Visualizes and optimizes portfolios based on US stocks using MPT.
MPT.py	Advanced version of Markowitz with 30,000 simulations for portfolio selection.
MPTindia.py	Extends MPT to Indian equities using historical NSE data.
📌 Key Features

    CAPM Analysis

        Beta estimation (covariance and regression method)

        Alpha-beta scatter plot

        Expected return calculation using market data

    Bond Pricing

        Present value calculation of coupons and principal

        Flexible inputs for coupon rate, maturity, and market return

    Modern Portfolio Theory (MPT)

        Monte Carlo simulation of thousands of portfolios

        Risk-return scatter plot with Sharpe ratio coloring

        Sharpe-optimal portfolio identification using SciPy optimizer

    Indian Market Support

        MPTindia.py uses nsepy for fetching NIFTY 50 historical data

        Optimization of portfolios for Indian equities with visualization

🚀 Getting Started
🔧 Prerequisites

Install the necessary libraries:

pip install numpy pandas yfinance matplotlib scipy nsepy

    Note: nsepy may require additional dependencies or setup for some environments.

🧪 How to Run

Each script has a standalone __main__ block. Simply run:

python CAPM.py

Or replace with any of the other files depending on the model you want to execute.
📊 Sample Output

    CAPM regression plots with alpha and beta

    Efficient frontier of simulated portfolios

    Optimal Sharpe ratio points

    Calculated bond price

💡 Future Improvements

    Add UI using Streamlit for interactive financial analysis

    Support for multiple bonds and batch portfolio strategies

    Integration with SQL or cloud data sources for large-scale analytics

📝 License

This project is open-source and available under the MIT License.
🤝 Contributing

Feel free to fork, open issues, or submit pull requests to expand this repository with more financial models or improvements!
