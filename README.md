# Data Analysis Projects

This repository contains two data analysis projects focusing on different domains: Air Quality Index (AQI) and Population Analysis in India, and Analyzing Senator Stock Trades for Potential Insider Trading. Each project is hosted in its respective subdirectory, complete with documentation, code, and data files.

## Project 1: Analyzing Senator Stock Trades for Potential Insider Trading

This project investigates whether a senator engaged in insider trading by analyzing their publicly reported stock trades and comparing them to the fluctuations in stock prices during the relevant time frame. The focus of this analysis is on Senator Nanci Pelosi and her trades in Nvidia, Tesla, and Microsoft stocks.

The project utilizes Python and data analysis libraries such as Pandas to process and analyze the stock trading data. The analysis involves the following steps:

1. Data Preprocessing: Converting CSV files into DataFrames, cleaning and preprocessing the data, and merging the stock trading data with the corresponding stock price data.

2. Computation: Calculating metrics such as total profit/loss, percentage returns, cost of trades, and return on investment (ROI). The ROI and effective ROI (eROI) are compared to market standards and thresholds to identify potentially unusual or suspicious trades.

3. Analysis and Conclusions: Analyzing the computed metrics and comparing them to market standards to determine if there are any signs of potential insider trading based on abnormally high returns and eROI values.

The project data is stored in CSV files and includes Senator Nanci Pelosi's stock trading history, NASDAQ stock market index historical price data, and historical price data for individual stocks like Tesla, Microsoft, and Nvidia.

For more detailed information, please refer to the [README.md](stock-trade-analysis/README.md) file in the `stock-trade-analysis` subdirectory.


## Project 2: Air Quality Index and Population Analysis in India

This project aims to analyze the Air Quality Index (AQI) data of various states in India and their respective population to identify any correlations between pollution levels and population density. Additionally, the project aims to identify states with ozone levels below the national threshold, which could potentially lead to the formation of ozone holes if not addressed promptly.

The project utilizes two main datasets:

1. **Indian Cities Database**: This dataset contains information about Indian cities, including their respective states, cities, and details on the quantities of different pollutants such as NO2, CO, OZONE, and more.

2. **Indian Census Bureau Demographic Dataset**: This dataset provides demographic information about Indian states and union territories.

The analysis is performed using Python and various data analysis libraries such as Pandas, NumPy, and Matplotlib. The results of the analysis are presented through visualizations and insights, highlighting the states that need immediate policy changes to address low ozone levels.

For more detailed information, please refer to the [README.md](air-quality-analysis/README.md) file in the `air-quality-analysis` subdirectory.

## Contributing

Contributions to these projects are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This repository is licensed under the [MIT License](LICENSE).