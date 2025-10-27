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
| Category            | Tools / Libraries                       |
| ------------------- | --------------------------------------- |
| Environment         | **Google Colab**                        |
| Language            | **Python**                              |
| Data Analysis       | **Pandas**, **NumPy**                   |
| Visualization       | **Matplotlib**, **Seaborn**, **Plotly** |
| clustering analysis | **Elbow Method** , **K-Means**          |

📜 **Python Script:**
[Python_Analysis_Script.ipynb](https://github.com/Kshitija-Agrawal/Traffic-Data-Analysis/blob/main/traffic_internship_ML.ipynb)

---

## 🧩 Dataset Information
The dataset includes:
- **Title Lookup Table** – Contains page or content titles  
- **Keyword Lookup Table** – Stores keyword metadata and performance metrics  
- **Traffic Data Table** – Tracks keyword ranking, traffic cost, and trends  

🔗 **Dataset Source:** 
[Traffic Data.xlsx](https://github.com/Kshitija-Agrawal/Traffic-Data-Analysis/blob/main/traffic%20data%20set.xls)

---

## ⚙️ Tools & Technologies Used
| Tool | Purpose |
|------|----------|
| **Excel** | Data cleaning, transformation, and lookup-based table creation |
| **MySQL** | Database design and EER modeling |
| **Power BI** | Dashboard and visualization |
| **Python** | EDA, clustering, and statistical analysis |

---

## 🏁 Key Outcomes
- Built a **fully relational data model** linking keywords, titles, and traffic metrics.  
- Designed a **dynamic Power BI dashboard** for real-time insights.  
- Automated further analysis through **Python scripting**.  
- Demonstrated complete **data lifecycle management** from Excel to visualization.

---

## 📂 Project Files
| File Name | Description |
|------------|-------------|
| `Tables` | Raw and cleaned dataset |
| `traffic data set.xls` | dataset |
| `Traffic-dashboard.png` | Power BI dashboard image |
| `EER diagram.png` | Entity Relationship Diagram |
| `traffic-internship.pbix` | Power BI dashboard |
| `traffic_internship_ML.ipynb` | Python data analysis script |

---

## 👩‍💻 Author
**Kshitija Agrawal**  
📧 *[kshitijaagrawal2@gmail.com]*  
💼 *[https://www.linkedin.com/feed/?trk=guest_homepage-basic_google-one-tap-submit]*  



  
