# 💱 Currency Exchange ETL Project

## 📌 Project Overview

This project demonstrates an **ETL (Extract, Transform, Load)** pipeline using live **currency exchange rate data**. It is built using Python and Jupyter Notebook to showcase data collection from an API, cleaning and transforming the data, and deriving simple analytical insights.

> 📅 Date of data: 23 July 2025  
> 📌 Base currency: USD

---

## 🔧 Tools & Libraries Used

- `requests` – for extracting data from API  
- `pandas` – for data cleaning and transformation  
- `matplotlib` – for data visualization  
- Jupyter Notebook (Python 3)

---

## 📊 Project Workflow

### 1. Extract
Data was fetched from the **ExchangeRate.host API**, providing the latest currency rates based on a specified base currency (USD).

### 2. Transform
- Converted raw JSON into a structured DataFrame  
- Parsed timestamp and formatted dates  
- Sorted exchange rates to identify strongest currencies  
- Cleaned and standardized columns for analysis

### 3. Load
- Final DataFrame saved as `exchange_rates.csv`  
- Optional PNG export of top currency chart for documentation

---

## 📈 Key Insight

> Top 10 strongest currencies (value **higher** than USD per unit) include:
- KWD (Kuwait Dinar)
- BHD (Bahraini Dinar)
- OMR (Omani Rial)
- JOD (Jordanian Dinar)
- GBP, EUR, CHF, etc.

These currencies are typically backed by:
- Strong monetary policy
- Export-driven economies (e.g., oil)
- Low inflation and economic stability

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `CurrencyExchange_ETL.ipynb` | Main Jupyter Notebook |
| `CurrencyExchange_ETL.pdf` | PDF version of notebook |
| `exchange_rates.csv` | Cleaned data file (output of ETL) |
| `top_10_currency_chart.png` | Visualization of strongest currencies |
| `requirements.txt` | Python libraries used |

---

## 🧠 Next Steps (Optional Ideas)

- Automate daily data collection and build time series
- Compare historical trends in currency strength
- Load data into SQL or create interactive dashboards

---

## 🙋‍♂️ About Me

**Muhammad Hafizd Ramadhan**  
Aspiring Data Analyst | Python & SQL Enthusiast  
📧 muh.hafizdramadhan@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/muhammadhaf)

