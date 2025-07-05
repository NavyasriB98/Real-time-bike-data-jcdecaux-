# Real-time-bike-data-jcdecaux-
The data was collected using a real-time bike-sharing API with an API key in Python. The requests library was used to fetch the data at regular intervals, and the results were stored in CSV format using pandas. After collecting the data, it was cleaned by handling missing values, filtering out invalid records, and converting time-related columns into the correct format. Once cleaned, the data was analyzed using pandas and numpy to explore usage patterns, identify the busiest stations, and observe trends over time.


📌 **Project Overview**
⏱️ Real-time data collection using JCDecaux's public API (scheduled hourly).

📊 Exploratory Data Analysis on bike usage trends.

🧹 Data cleaning: missing values, formatting timestamps, invalid records.

📆 Temporal pattern analysis across days, hours, weekdays vs. weekends.

🏙️ Analysis spans multiple cities via contractName.

🛠️ **Technologies Used**
Tool/Library	Purpose
Python	Core language
Pandas	Data manipulation and analysis
NumPy	Numerical operations
Requests	API calls to JCDecaux
Time / Datetime	Handling timestamps
CSV	Data storage for further analysis

 **How the Data is Collected**
Data is pulled from the JCDecaux API using your API key.

A Python script runs on a scheduler (e.g., hourly) to store snapshots of all stations.

Data is appended to a CSV file (bikes.csv) for persistence.


**Exploratory Data Analysis (EDA)**
✅ Data Cleaning
Remove records with missing or corrupt fields

Convert last_update to human-readable timestamps

Filter for valid city names, station status (OPEN)

📈 **Key Analyses**
📆 Bike availability across weekdays vs. weekends

🕒 Hourly availability trends (morning/evening patterns)

📍 Busiest stations based on bike demand

🔁 Trends over time (daily usage, availability drops)
