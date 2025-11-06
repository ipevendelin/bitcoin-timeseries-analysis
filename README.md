# Bitcoin Time-Series Analysis and Modeling

Bitcoin historical time-series analysis and modeling project. This repository contains exploratory data analysis, time-series visualization, decomposition, autocorrelation analysis, and partition planning for predictive model formation.

## Project Overview

This project aims to analyze Bitcoin's historical price data using advanced time-series techniques, including:
- Time-series visualization and exploratory analysis
- Trend and seasonality decomposition
- Autocorrelation analysis
- Data partitioning strategies for model validation

## Project Structure

```
bitcoin-timeseries-analysis/
├── README.md
├── notebooks/
│   ├── kaggle/              # Kaggle notebooks
│   └── local/               # Local Jupyter notebooks
└── report/
    └── analysis_report.md   # Main reporting document
```

### Folders

- **notebooks/**: Contains Jupyter notebooks for analysis and experimentation
  - `kaggle/`: Notebooks developed in Kaggle environment
  - `local/`: Local notebooks for development and testing
  
- **report/**: Contains the main analysis reporting document with findings and insights

## Analysis Sections

### 1. Time-Series Visualization and Exploratory Analysis (0.5p)
- Visual representation of Bitcoin historical price data
- Identification of trends, patterns, and anomalies
- Basic statistical summary and initial insights

**Resources:**
- [Pandas Time-Series Documentation](https://pandas.pydata.org/docs/user_guide/timeseries.html)
- [Matplotlib for Time-Series](https://matplotlib.org/)
- [Seaborn Visualization](https://seaborn.pydata.org/)

### 2. Time-Series Decomposition (0.5p)
- Long-term trend analysis
- Seasonality patterns
- Residual component analysis

**Resources:**
- [Python: STL Decomposition (statsmodels)](https://www.statsmodels.org/dev/examples/notebooks/generated/stl_decomposition.html)
- [MATLAB: Trend Decomposition](https://se.mathworks.com/help/matlab/ref/double.trenddecomp.html)

### 3. Autocorrelation Analysis (0.5p)
- ACF (Autocorrelation Function) plots
- PACF (Partial Autocorrelation Function) analysis
- Stationarity testing

**Resources:**
- [Python: Autocorrelation Calculation](https://www.geeksforgeeks.org/how-to-calculate-autocorrelation-in-python/)
- [MATLAB: Autocorr Function](https://se.mathworks.com/help/econ/autocorr.html)

### 4. Time-Series Partition Planning (0.5p)
- Training/validation/test split strategy
- Walk-forward validation approach
- Cross-validation considerations for time-series data

**Resources:**
- [MATLAB: Time-Series Partitioning](https://se.mathworks.com/help/stats/tspartition.html)
- [Python: Cross-Validation in Time-Series](https://medium.com/@soumyachess1496/cross-validation-in-time-series-566ae4981ce4)

## Data Source

Bitcoin historical data can be obtained from:
- [Kaggle Bitcoin Datasets](https://www.kaggle.com/datasets)
- [CoinGecko API](https://www.coingecko.com/api)
- [Yahoo Finance](https://finance.yahoo.com/)

## Getting Started

1. Clone the repository
2. Explore notebooks in `notebooks/` folder
3. Review analysis report in `report/analysis_report.md`
4. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels scikit-learn jupyter
   ```

## Technologies Used

- **Python 3.8+**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib & Seaborn**: Data visualization
- **Statsmodels**: Statistical modeling and time-series analysis
- **Scikit-learn**: Machine learning utilities
- **Jupyter**: Interactive notebooks

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for improvements.

## License

This project is open source and available under the MIT License.

## Author

Created for time-series analysis and modeling coursework.
