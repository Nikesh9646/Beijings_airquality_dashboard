# Beijing Air Quality Analysis – Power BI Dashboard

## 📌 Project Overview
This project focuses on analyzing **air quality trends in Beijing** using environmental and pollution data.  
An interactive **Power BI dashboard** was built to understand seasonal variations, identify major pollutants, and study the relationship between weather conditions and air pollution.

The goal of this project is to transform raw, real-world environmental data into **meaningful insights** that can support data-driven decision-making.

---

## 🎯 Project Objectives
- Analyze **temperature and humidity trends** across different months
- Study major air pollutants such as **Carbon Monoxide, Nitrogen Dioxide, Nitrogen Oxides, Benzene, and Non-Methane Hydrocarbons**
- Identify **key contributors** to air pollution
- Observe **seasonal patterns** affecting air quality
- Build an **interactive and user-friendly Power BI dashboard**

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **Power Query** – Data cleaning and transformation
- **DAX** – Calculated measures and aggregations
- **Data Modeling**
- **Data Visualization**

---

## 🧹 Data Cleaning & Transformation
Raw environmental datasets often contain missing, inconsistent, or invalid values.  
The following preprocessing steps were performed using **Power Query in Power BI**:

- Combined separate **Date** and **Time** columns into a single **DateTime** column to enable proper time-series analysis.
- Converted the merged column to the correct **Date/Time data type** for monthly and yearly trend analysis.
- Identified invalid sensor readings represented by **-200 values** across multiple columns.
- Replaced all **-200 values** with the **respective column averages** to handle missing or erroneous data without losing records.
- Renamed abbreviated column names into **clear, meaningful names** for better readability and understanding.  
  - Example:  
    - `CO` → Carbon Monoxide  
    - `NO2` → Nitrogen Dioxide  
    - `NOx` → Nitrogen Oxides
- Ensured data consistency and improved data quality for accurate analysis and visualization.

---

## 📊 Dashboard Preview
![Beijing Air Quality Dashboard](screenshots/air_quality_dashboard.png)

---

## 🔍 Key Insights
- Air pollution levels are **higher during winter months** compared to summer.
- **Nitrogen-based pollutants** are the dominant contributors to air quality degradation.
- Weather parameters such as **temperature and humidity** significantly influence pollution levels.
- Seasonal trends play a major role in air quality variations across the year.

---

## 📂 Repository Structure
beijing-air-quality-analysis-powerbi/
│
├── data/
│ └── beijing_air_quality.csv
│
├── dashboard/
│ └── Beijing_Air_Quality.pbix
│
├── screenshots/
│ └── air_quality_dashboard.png
│
├── insights/
│ └── key_findings.md
│
└── README.md


## 👤 Author
**Nikesh Penala**  
Aspiring Data Analyst  
Skills: Power BI | SQL | Python | Excel | Data Visualization

---

⭐ If you found this project interesting, feel free to star the repository!
