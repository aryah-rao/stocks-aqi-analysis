# Air Quality Index and Population Analysis in India

This project aims to analyze the Air Quality Index (AQI) and population data of various states in India to determine if there is any correlation between pollution levels and population. The analysis also identifies states that have ozone levels below the national threshold, indicating a need for immediate policy changes to address the issue.

## Table of Contents
- [Introduction](#introduction)
- [Data Sources](#data-sources)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Air pollution is a significant concern in India, affecting the health and well-being of millions of people. This project focuses on analyzing the AQI data of various states in India and their respective population to identify any correlations between pollution levels and population density. Additionally, the project aims to identify states with ozone levels below the national threshold, which could potentially lead to the formation of ozone holes if not addressed promptly.

## Data Sources
The project utilizes two main datasets:
1. Indian Cities Database: This dataset contains information about Indian cities, including their respective states, cities, and details on the quantities of different pollutants such as NO2, CO, OZONE, and more. The dataset is obtained from [Kaggle](https://www.kaggle.com/datasets/kdsharmaai/india-city-air-quality-index?select=India_city_polution_data.xml) and is licensed under the Open Database License.
2. Indian Census Bureau Demographic Dataset: This dataset provides demographic information about Indian states and union territories, sourced from the [Indian Census Bureau](https://en.wikipedia.org/api/rest_v1/page/html/List_of_states_and_union_territories_of_India_by_population). The dataset is in the public domain.

## Project Structure
The project repository has the following structure:
├── data/   \
│   ├── pollution.xml   \
│   └── ... \
├── dbfiles/    \
│   └── india.db    \
├── img/    \
│   └── img.png \
├── modules/    \
│   └── util.py \
├── creds.json  \
├── data_acquisition.ipynb  \
├── data_analysis.ipynb \
└── README.md   \

- The `data/` directory contains the raw data files used in the project.
- The `dbfiles/` directory contains the SQLite database file (`india.db`) used for storing the processed data.
- The `img/` directory contains any images used in the project or generated during the analysis.
- The `modules/` directory contains utility modules used in the project.
- The `creds.json` file contains the necessary credentials for connecting to the database.
- The `data_acquisition.ipynb` notebook contains the code for data acquisition, cleaning, and storage in the database.
- The `data_analysis.ipynb` notebook contains the code for data analysis, visualization, and insights.

## Dependencies
The project requires the following dependencies:
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- SQLite3
- requests
- lxml

## Usage
1. Clone the repository: 'git clone https://github.com/your-username/your-repo.git'

2. Install the required dependencies as mentioned in the [Dependencies](#dependencies) section.

3. Run the `data_acquisition.ipynb` notebook to acquire and preprocess the data.

4. Run the `data_analysis.ipynb` notebook to perform the analysis and generate visualizations.

## Results
The analysis reveals that certain states in India have ozone levels below the national threshold, indicating a need for immediate policy changes to prevent the potential formation of ozone holes. Furthermore, the analysis shows that there is no significant correlation between high population and pollution levels, contradicting the claims made by the Indian government that pollution is solely due to a larger population.

## Conclusion
Based on the findings, it is evident that India overall has high pollution levels, and priority should be given to implementing policy recommendations, particularly in states with ozone levels below the national threshold. The project highlights the importance of data-driven decision-making in addressing environmental concerns and the need for targeted actions to mitigate air pollution in India.

## Contributing
Contributions to the project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).