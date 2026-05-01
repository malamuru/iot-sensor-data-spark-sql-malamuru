<h1 align="center"> IoT Sensor Data Analysis using Apache Spark SQL</h1>

<h3 align="center">
Big Data Analytics Project | PySpark | Spark SQL | Data Engineering
</h3>

<p align="center"><em>"Transforming raw IoT sensor data into meaningful insights using scalable data processing."</em></p>

---

## ✨ Overview

This project focuses on analyzing **IoT sensor data** using **Apache Spark SQL** to extract meaningful insights from environmental readings such as temperature, humidity, timestamp, and location.

It demonstrates how large-scale sensor data can be processed using **distributed data processing techniques**, enabling efficient analysis of trends, patterns, and anomalies.

---

##  Key Features

- 📥 Data ingestion and schema exploration using PySpark  
- 🌡️ Filtering and validation of sensor readings  
- 📊 Aggregation of temperature and humidity by location  
- ⏰ Time-based trend analysis (hourly insights)  
- 🏆 Sensor ranking using window functions  
- 📌 Pivot table generation for comparative analysis  
- 📁 Exporting processed results into structured CSV outputs  

---

## 🧠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Spark SQL](https://img.shields.io/badge/Spark%20SQL-FF6F00?style=for-the-badge)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)

---

## 📂 Project Structure

- sensor_data.csv
- task1.py # Data loading & exploration
- task2.py # Filtering & aggregation
- task3.py # Time-based analysis
- task4.py # Window functions & ranking
- task5.py # Pivot table analysis

---

## 📊 Project Structure

| Column        | Description |
|--------------|------------|
| sensor_id    | Unique sensor identifier |
| timestamp    | Time of reading |
| temperature  | Temperature (°C) |
| humidity     | Humidity (%) |
| location     | Sensor location |
| sensor_type  | Type of sensor |

---

## 🔍 Analysis Performed

### 📌 Data Exploration
- Loaded dataset into Spark DataFrame  
- Explored schema and distinct locations  

### 📌 Filtering & Aggregation
- Removed out-of-range temperature values  
- Calculated average temperature and humidity by location  

### 📌 Time-Based Analysis
- Extracted hour from timestamp  
- Analyzed hourly temperature trends  

### 📌 Ranking Analysis
- Used **DENSE_RANK()** to rank sensors by temperature  
- Identified top sensors  

### 📌 Pivot Analysis
- Created pivot tables (location vs hour)  
- Compared temperature trends across locations  

---

## ⚙️ How to Run

```bash
pip install pyspark

python task1.py
python task2.py
python task3.py
python task4.py
python task5.py
