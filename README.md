# IPD Innovative Project Development

This repository contains Python code for the IPD Innovative Project Development project. The code performs various tasks related to traffic analysis and aggregation of traffic metrics.

## Data Preparation

The provided Python code includes data preparation steps to analyze traffic speeds. It uses the `pandas` library to read and process the data. The code reads a compressed CSV file (`Mumbai.csv.gz`) containing traffic speed information.

### Representing One Point in Time

The code snippet labeled "Represent one point in time" represents a specific point in time by selecting specific columns from the dataset. It creates a new DataFrame (`monday_9am`) that contains the selected columns. The resulting DataFrame is then saved as a CSV file (`9am_speeds.csv`).

### Calculating Aggregated Traffic Metrics

The code snippet labeled "Calculate aggregated traffic metrics" calculates aggregated traffic metrics based on the traffic speeds. It selects a range of columns from the dataset that represent a specific time interval (9 AM to 10 AM). It then calculates the average speed across the selected time interval for each node. The resulting DataFrame (`monday_9_10_nodes_speeds`) includes the start node, end node, and average speed for each node.

## Usage

To use this code, follow these steps:

1. Ensure that you have Python installed on your system.

2. Install the required dependencies by running `pip install pandas` in your terminal or command prompt.

3. Place the `Mumbai.csv.gz` file in the same directory as the Python script.

4. Open the Python script and run it using a Python interpreter.

5. The script will perform the specified data preparation tasks and display the results in the console.

6. The resulting data, such as the `9am_speeds.csv` file or the `monday_9_10_nodes_speeds` DataFrame, can be further analyzed or utilized for your project's needs.

## License

This project does not have a specific license as the provided code snippets are for demonstration purposes only. Please refer to the original source of the data for any licensing requirements.

## Acknowledgements

The IPD Innovative Project Development project and the code snippets provided are created by the project developers. Special thanks to the developers for sharing their code and contributing to the field of traffic analysis.
