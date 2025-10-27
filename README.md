# 🚦 Traffic Data Analysis Project

## 📘 Overview
This project focuses on analyzing **traffic and keyword performance data** by integrating Excel, SQL, Power BI, and Python.  
It provides a complete end-to-end data analytics workflow — from data modeling and visualization to advanced analysis.

---

## 🧭 Project Workflow

### **Step 1: Data Modeling in Excel**
- Created **Fact** and **Dimension** tables using **Excel Lookup formulas (VLOOKUP & XLOOKUP)**.
- Structured the dataset into:
  - **Fact Table:** `traffic_data`
  - **Dimension Tables:** `title_lookup`, `keyword_lookup`
- Cleaned and normalized raw traffic data for efficient querying and relational design.

📁 **File:**
     [traffic\_Data.csv](https://github.com/Kshitija-Agrawal/Traffic-Data-Analysis/tree/main/Tables)
---

### **Step 2: EER Diagram in SQL**
- Imported the cleaned Excel files into a **MySQL database**.
- Established **primary and foreign key relationships**.
- Designed an **Entity-Relationship (EER) Diagram** to visualize data relationships between tables.

📊 **EER Diagram:**
![EER Diagram](https://github.com/Kshitija-Agrawal/Traffic-Data-Analysis/blob/main/EER%20diagram.png)

**Tables Created:**
1. `title_lookup`  
2. `keyword_lookup`  
3. `traffic_data`

---

### **Step 3: Interactive Dashboard in Power BI**
- Connected the MySQL data to **Power BI**.
- Built an **interactive dashboard** for keyword and traffic analysis.
- Visualized:
  - Keyword performance metrics
  - CPC and competition trends
  - Traffic distribution by title and keyword
  - Search volume insights

📊 **Power BI File:**
    [traffic\_Analysis\_Dashboard.pbix](https://github.com/Kshitija-Agrawal/Traffic-Data-Analysis/blob/main/traffic-internship.pbix)

---

### 🐍 **Step 4: Python Analysis**
Performed advanced analytics using **Python** to explore and cluster keyword performance data.

#### 🔍 **Key Python Tasks**
- Data preprocessing using `pandas` and `numpy`
- Exploratory Data Analysis (EDA) with `matplotlib` and `seaborn`
- **Elbow Method** to determine the optimal number of clusters  
- **K-Means Clustering** to group keywords based on performance metrics such as:
  - Search Volume  
  - Traffic Cost  
  - CPC  
  - Competition  

#### 📜 **Python Libraries Used**
```python

  
