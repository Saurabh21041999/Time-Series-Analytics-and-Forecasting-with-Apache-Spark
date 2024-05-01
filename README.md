# Time Series Forecasting Project

This project focuses on time series forecasting using the Prophet model. The project is built on top of Spark libraries and predefined installed libraries as provided in Lab 2.

## Steps to Run

1. Clone this repository.

2. Install all libraries mentioned in requirement.txt

3. Each notebook file is associated with one of the dataset folders provided, as the project gradually increases the data points to observe the performance improvement of the Prophet model.
   - For example, `time_series_forecasting_5_years.ipynb` will work with the data provided in the `data/5_years` directory.

7. Run code snippets provided in `.ipynb` file.

## Directory Structure

The project directory should have the following structure:

```
.
├── data/
│   ├── weather.csv
│   ├── 1_year/
│   ├── 3_years/
│   ├── 5_years/
│   └── 8_years/
├── code/
    ├── time_series_forecasting_1_years.ipynb
    ├── time_series_forecasting_3_years.ipynb
    ├── time_series_forecasting_5_years.ipynb
    └── time_series_forecasting_8_years.ipynb
```

- `data/`: Contains the dataset files
  - `weather.csv`: Contains NY weather data
  - `1_year/`: Contains CSV data files from Jan 2023 to Feb 2024
  - `3_years/`: Contains CSV data files from Jan 2021 to Feb 2024
  - `5_years/`: Contains CSV data files from Jan 2019 to Feb 2024
  - `8_years/`: Contains CSV data files from Jan 2016 to Feb 2024
- `code/time_series_forecasting_*.ipynb`: Jupyter Notebook files for different dataset sizes


