# Precipitation Seattle vs Orlando

> A brief description of what the project does and its purpose.
> 
> This project aims to find out which city, Seattle or Orlando, recieves more precipitation based on data collected from 2018-2022 from NOAA.
---

## Project Overview

This project aims to find out which city, Seattle or Orlando, recieves more precipitation on avgerage based on data collected from 2018-2022. It looks at average precipitation monthly, as well as average number of days of precipitation by month. This project found that Orlando recieves more precipitation overall but this is due to heavy inconsistent rainfall compaired to Seattle's more consistent light rainfall.

- **Objective:** Find if Seattle or Orlando recieves more annual precipitaion
- **Domain:** Environmental / Climate Data Analysis
- **Key Techniques:** Data Cleaning, Data Visualization, Hypothesis Testing (t-tests, z-tests), Time Series Aggregation

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** [Link to the data source(s)](https://www.ncei.noaa.gov/cdo-web/search) 
- **Description:** Weather data over 5 years (user selected dates of 2018-2022) coming from one station (user selected station) in Seattle and Orlando.
- **License:** This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Analysis

The analysis was conducted using two Jupyter notebooks. The ORL_SEA_data_cleaning.ipynb notebook performs all data cleaning and preparation steps, including loading the raw precipitation data, converting data types, keeping only relevant columns, handling missing values, and joining the Orlando and Seattle datasets into a single tidy format.

The Analysis_clean_data.ipynb notebook carries out the statistical and visual analyses. It includes calculations of monthly and daily precipitation statistics, t-tests and z-tests, and the creation of visualizations comparing precipitation in the two cites.

To reproduce the results, run the notebooks in the following order:
ORL_SEA_data_cleaning.ipynb
Analysis_clean_data.ipynb

---

## Results

Seattle experiences precipitation on a greater proportion of days throughout the year, while Orlando tends to receive heavier rainfall over fewer days. Statistical tests revealed significant differences in both mean precipitation and precipitation frequency across most months. Main take away: Seattle has more days of precipitation, Orlando gets more precipitation in inches overall.

---

## Authors

- Your Name - [@naomi-rlm](https://github.com/naomi-rlm)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used
- Tutorials or papers referenced
- Inspiration or collaborators
