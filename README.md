# 📊 COVID-19 Time Series Analysis

## 📌 Project Overview | SyntecxHub

This project performs **time series analysis of COVID-19 data** to understand how the pandemic evolved over time in different countries.
The analysis focuses on computing **daily cases, weekly cases, rolling averages**, detecting **peak infection periods**, and comparing trends across countries.

The goal is to demonstrate **data analysis and visualization skills using Python**.

---

## 🎯 Objectives

* Load and explore a COVID-19 dataset
* Perform **country-wise time series analysis**
* Compute **daily cases and weekly cases**
* Use **rolling averages to smooth noise**
* Compare COVID-19 trends between countries
* Detect **peak infection dates**
* Export charts and summarize insights

---

## 📂 Dataset

The dataset contains global COVID-19 statistics including:

* Date
* Country
* Confirmed cases
* Deaths
* Recovered cases
* Active cases
* New cases
* New deaths
* New recovered
* WHO Region

The dataset provides **daily updates for multiple countries**.

---

## 🛠 Tools & Technologies

* **Python**
* **Pandas** – data manipulation
* **Matplotlib** – data visualization
* **Jupyter Notebook**

---

## 📊 Project Workflow

### 1️⃣ Data Loading

Load the dataset using Pandas and inspect its structure.

### 2️⃣ Country Filtering

Select specific countries for analysis:

* Albania
* Zimbabwe
* Afghanistan
* Zambia

### 3️⃣ Daily Case Analysis

Compute **daily new cases** and visualize trends using a **line chart**.

### 4️⃣ Weekly Case Analysis

Calculate **weekly cases using a 7-day rolling window** to observe broader trends.

### 5️⃣ Rolling Average (Noise Reduction)

Apply **7-day rolling averages** to smooth daily fluctuations and reveal clearer trends.

### 6️⃣ Country Comparison

Compare the pandemic trends across multiple countries using time series plots.

### 7️⃣ Peak Detection

Identify the **date with the highest number of daily cases** for each country.

### 8️⃣ Export Charts

Save visualizations as image files for reporting and presentation.

---

## 📈 Key Visualizations

The project includes the following charts:

* Daily COVID-19 cases over time
* Weekly COVID-19 cases trend
* Country comparison using rolling averages
* Peak case detection analysis

---

## 🔎 Key Insights

* Daily case data contains high variability and noise.
* Applying a **7-day rolling average** provides a clearer trend of infection spread.
* Different countries experienced **peaks at different times**, showing variations in outbreak intensity.
* Time series visualization helps identify **growth phases and decline phases** of the pandemic.

---

## 📁 Project Structure

```
COVID19_TimeSeries_Analysis
│
├── covid_analysis.ipynb
├── covid_data.csv
├── charts/
│   ├── daily_cases.png
│   ├── weekly_cases.png
│   └── country_comparison.png
│
└── README.md
```

---

## 🚀 Future Improvements

* Add interactive dashboards using **Plotly or Power BI**
* Perform **advanced time series forecasting**
* Build **predictive models for case trends**

---

## 👨‍💻 Author

**Bhaskar Mandal | IIT KGP**

*Data Analyst Intern @SyntecxHub*
