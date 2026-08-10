# Cruiser-ship_Reservations_Kaggle_Dataset
###  Data Processing & Analytical Pipeline

I analyzed a dataset containing 70,000 cruise ship reservations sourced from Kaggle. 

First, I performed comprehensive data cleaning and preprocessing using Python's core data analysis libraries, primarily **Pandas**. Once the data was structured and refined, I leveraged **DuckDB** (executed via pipeline queries) to extract four specific analytical views from the raw dataset. These views were engineered to unlock key business insights by addressing the following core questions:

1. **Ship & Cruise Line Performance:** Which ship or company achieved the best financial and operational results? *(Query 1)*
2. **Route Popularity & Profitability:** Which route types proved to be the most popular and financially lucrative? *(Query 2)*
3. **Lead Time Analysis:** How do customer satisfaction, per-capita spending, and generated revenue vary across different booking windows and planning horizons? *(Query 3)*
4. **Seasonality & Revenue:** How does total revenue fluctuate across different seasons of the year? *(Query 4)*

#### 🛠️ Tech Stack & Tools Used
* **Language:** Python
* **Data Wrangling:** Pandas, NumPy
* **SQL Engine / Pipeline:** DuckDB
* **Data Visualization:** Tableau Public
* **Source Dataset:** Kaggle (70,000 cruise ship reservations)
