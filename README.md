# Japan CPI Data Analysis & Volatility

An economic data analysis project exploring long-term Consumer Price Index (CPI) trends in Japan from 1970 to 2022. The analysis examines how price movements and volatility differed across categories such as food, housing, energy, medical care, and education.

The project uses exploratory data analysis, year-over-year CPI changes, volatility analysis, rolling volatility, and historical event markers to examine changes in price behavior over time.

## Research Question

**What categories show the highest volatility in Japan's CPI over the past 50 years?**

## Key Features

* **Exploratory Data Analysis:** Analyzes CPI trends across a wide range of goods and services.
* **Volatility Analysis:** Compares categories using the standard deviation of year-over-year percentage changes.
* **Rolling Volatility:** Uses a 5-year rolling window to examine changes in price volatility over time.
* **Historical Events:** Places major economic events alongside CPI trends for context.
* **Category Comparisons:** Examines differences between energy, food, housing, medical care, education, and other sectors.
* **Data Visualization:** Uses line plots, box plots, and volatility charts to identify long-term patterns.

## Historical Events

The analysis includes markers for:

* 1973 Oil Shock
* 1979 Oil Shock
* Japan's Lost Decade (1991–2001)
* 2008 Financial Crisis
* COVID-19 (2020)

These events provide context for examining changes in CPI levels and volatility over time.

## Dataset

**Consumer Price Index of Japan by 2022**

Source: Kaggle

https://www.kaggle.com/datasets/yutodennou/consumer-price-index-of-japan-by-2022

The dataset contains annual CPI data covering multiple categories of goods and services.

## Results at a Glance

* Energy categories such as **Gas, Electricity, and Other Fuel & Light** showed some of the highest volatility.
* **Housing and Rent** generally showed more gradual and stable long-term price movements.
* **Food categories** experienced short-term price shocks and periods of increased volatility.
* **Medical Care and Medical Services** showed relatively gradual long-term increases compared with more volatile categories.
* Major economic events correspond with visible changes in CPI trends and volatility across several categories.

## Methodology

### 1. Data Collection

The project uses Japan CPI data from the Kaggle dataset:

**Consumer Price Index of Japan by 2022**

The dataset contains multiple CPI classifications covering categories of goods and services.

### 2. Data Cleaning

Four datasets were loaded and examined:

* Goods & Services Classification
* Composite Index
* Middle-Level Classification
* Price Index by Items

Columns with insufficient data were removed, and missing observations in the selected price index data were excluded.

### 3. Volatility Analysis

Year-over-year percentage changes were calculated for CPI categories. Volatility was then measured using the standard deviation of these changes. The most and least volatile categories were identified and visualized.

### 4. Rolling Volatility

A 5-year rolling standard deviation was calculated for selected categories to examine how volatility changed over time.

Categories analyzed include:

* Electricity
* Education
* Food
* Fresh Vegetables
* Fruits
* Gas
* Housing
* Medical Care
* Medical Services
* Medicines & Health Fortification
* Other Fuel & Light
* Rent

## Visualizations

The project includes:

* CPI trend plots
* Top 15 most volatile categories
* Top 15 least volatile categories
* Box plots of CPI changes
* Category-level CPI trends with historical event markers
* 5-year rolling volatility plots

## Repository Contents

```text
CPI-Japan-Data-Analysis-Project/
│
├── CPI_Japan_Data_Analysis_Project.ipynb
├── CPI_Japan_Data_Analysis_Project_Slides.pdf
├── requirements.txt
├── README.md
└── Resources.txt
```

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* Kaggle


## Future Work

Potential extensions to this project include:

* Compare CPI volatility across countries such as Japan and the United States.
* Use time-series models such as ARIMA or LSTM to forecast CPI movements in volatile categories.
* Incorporate additional macroeconomic indicators such as wages, unemployment, and exchange rates.
* Explore relationships between CPI categories and broader economic conditions.
