# Forecasting Daily Bike Rental Demand

A data analysis project for forecasting daily bike rental demand using time series models in R.

## Table of Contents
- [About the Project](#about-the-project)
- [Data Description](#data-description)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data Analysis Steps](#data-analysis-steps)
- [Findings and Conclusions](#findings-and-conclusions)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## About the Project

This data analysis project focuses on forecasting daily bike rental demand using time series models in R. It includes data exploration, summary statistics, building time series models, and drawing conclusions based on the analysis.

## Data Description

The dataset contains daily counts of rental bike transactions between the years 2011 and 2012. It includes weather and seasonal information.

**Data Source:** [Bike Sharing Dataset](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset)

**Relevant Paper:** Fanaee-T, Hadi, and Gama, Joao. Event labeling combining ensemble detectors and background knowledge, Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing.

### Prerequisites

- [R](https://www.r-project.org/)
- [RStudio](https://www.rstudio.com/) (Optional but recommended)

### Installation

1. Clone the project repository:

2. Open the R project in RStudio.

3. Install required R packages by running the following command in the R console:
```R
install.packages("timetk")
install.packages("zoo")
install.packages("tseries")
install.packages("forecast")
install.packages("rmarkdown")

## Data Sources

- **Bike Rental Data**: [Capital bikeshare system dataset](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset)
- **Relevant Paper**: Fanaee-T, Hadi, and Gama, Joao. Event labeling combining ensemble detectors and background knowledge, Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg

## Data Analysis Steps

### 1. Data Exploration
- Load and examine the dataset.
- Calculate summary statistics.

### 2. Time Series Analysis
- Create interactive time series plots using `timetk`.
- Visualize seasonal diagnostics and anomalies.

### 3. Data Smoothing
- Smooth the time series data using Simple Exponential Smoothing and Simple Moving Average.
- Handle outliers and missing values.

### 4. Stationarity Assessment
- Check the stationarity of the time series using Augmented Dickey-Fuller (ADF) tests and autocorrelation plots.
- Apply differencing to make the data stationary.

### 5. ARIMA Modeling
- Fit manual and auto ARIMA models to the data.
- Evaluate model residuals for normality and patterns.
- Forecast the next 25 observations using both manual and auto ARIMA models.

## Contributing

Contributions are welcome! If you want to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Open a pull request to merge your changes into the main branch.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


## Acknowledgments

We would like to thank the authors of the Capital bikeshare dataset and the relevant paper for providing valuable data and insights.

Feel free to reach out if you have any questions or suggestions!
