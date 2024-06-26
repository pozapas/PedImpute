# [Imputing Time Series Pedestrian Volume Data with Consideration of Epidemiological-Environmental (EpiEnv) Variables](https://journals.sagepub.com/doi/10.1177/03611981241240758)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7194992.svg)](https://doi.org/10.1177/03611981241240758)

## Description
This project investigates the quality of pedestrian volume data for safety and urban planning purposes. Using statistical, machine learning, and deep learning methods, we detect anomalies in pedestrian activity data and impute missing values. We analyze daily time series data of pedestrian activity at traffic signals in the state of Utah from 2018 to 2022, incorporating Epidemiological-Environmental (EpiEnv) variables including average temperature, precipitation, air quality index, and COVID-19 data.
Our findings suggest the superiority of the DBSCAN method for anomaly detection and the effectiveness of Random Forest, LSTM, and GRU techniques in imputing various categories of missing value patterns. The results show the significant effect of EpiEnv variables on the process of anomaly detection and imputation across all traffic signals.

## Methodology
![Methodology](https://github.com/pozapas/PedImpute/blob/master/Images/Methodology.svg)

## Installation
This project and PedAnomaly.ipynb notebook require Python and the following Python packages installed:
- pandas
- numpy
- statsmodels
- matplotlib
- plotly
- scipy
- ruptures
- scikit-learn
- pyod
- datetime
- torch
- darts
  
To install the Python packages, navigate to the local directory where you have cloned this repository and run the following command:
```bash
pip install -r requirements.txt
```
You need to have a `requirements.txt` file in your repository for this command to work. To create one, you can use the `pip freeze` command, which outputs all of the packages in the current environment. You can redirect this output to a file using the following command:
```bash
pip freeze > requirements.txt
```
Then you can manually edit `requirements.txt` to only include the necessary packages.
