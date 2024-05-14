# Analyzing Senator Stock Trades for Potential Insider Trading

This project aims to investigate whether a senator engaged in insider trading by analyzing their publicly reported stock trades and comparing them to the fluctuations in stock prices during the relevant time frame. The focus of this analysis is on Senator Nanci Pelosi and her trades in Nvidia, Tesla, and Microsoft stocks.

## Project Overview

The main goal of this project is to determine if there are any signs of potential market manipulation or insider trading by examining the stock trades made by Senator Nanci Pelosi. The analysis involves comparing the senator's trades to the performance of the NASDAQ stock market during the same time period.

The project utilizes Python and various data analysis libraries such as Pandas to process and analyze the stock trading data. The data is stored in CSV files and is converted into DataFrames for efficient manipulation and computation.

## Data Sources

The project uses the following data sources:

1. `Nanci_history.csv`: Contains the history of Senator Nanci Pelosi's stock trades, including the company, buy/sell shares, and transaction date.
2. `Nasdaq.csv`: Provides historical price data for the NASDAQ stock market index.
3. `Tesla.csv`, `Microsoft.csv`, `Nvidia.csv`: Contain historical price data for Tesla, Microsoft, and Nvidia stocks, respectively.

## Analysis Methodology

The analysis involves the following steps:

1. Data Preprocessing:
   - Convert the CSV files into DataFrames using Pandas.
   - Clean and preprocess the data, including splitting the date column into separate day, month, and year columns.
   - Merge the stock trading data with the corresponding stock price data.

2. Computation:
   - Calculate metrics such as total profit/loss, percentage returns, and cost of trades using the `moneycalculator` function.
   - Compute the return on investment (ROI) for individual stocks and compare them to the ROI of the NASDAQ during the same time period using the `effective_ROI` function.
   - Determine if the ROI and effective ROI (eROI) exceed certain thresholds to identify potentially unusual or suspicious trades.

3. Analysis and Conclusions:
   - Analyze the computed metrics and compare them to market standards and thresholds.
   - Determine if there are any signs of potential insider trading based on the abnormally high returns and eROI values.
   - Provide conclusions and insights based on the analysis results.

## Repository Structure

- `main.ipynb`: Jupyter Notebook containing the main analysis code and documentation.
- `data/`: Directory containing the CSV files used in the analysis.
  - `Nanci_history.csv`: Senator Nanci Pelosi's stock trading history.
  - `Nasdaq.csv`: NASDAQ stock market index historical price data.
  - `Tesla.csv`, `Microsoft.csv`, `Nvidia.csv`: Historical price data for individual stocks.
- `README.md`: This file, providing an overview of the project and instructions for running the analysis.

## Running the Analysis

To run the analysis, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/your-repository.git`
2. Install the required dependencies: `pip install pandas numpy matplotlib`
3. Open the `main.ipynb` Jupyter Notebook.
4. Run the notebook cells in sequential order to execute the analysis.

## Disclaimer

This project is for educational and informational purposes only. The analysis and conclusions drawn from this project are based on the available data and should not be considered as financial advice or accusations of wrongdoing. The project authors do not claim any responsibility for the accuracy, completeness, or reliability of the data used in this analysis.

## License
This repository is licensed under the [MIT License](LICENSE).