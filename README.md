# 📊 DVD Rental Database Analysis Project

## 📋 Project Overview  
This project performs an in-depth analysis of the **dvdrental** sample database to uncover key business drivers and performance metrics.  

Using **SQL queries** executed via **Python’s SQLAlchemy** and **pandas** libraries, the analysis explores:  
- Customer behavior  
- Store performance  
- Inventory management  
- Sales trends  

The findings are visualized using **matplotlib** and **seaborn** to provide clear, actionable insights.  

---

## 💡 Key Insights & Findings  

### 📈 Strong Business Fundamentals  
- The business exhibits a **97.5% customer retention rate**.  
- Over **16,000 rentals** processed, showing a stable and engaged customer base.  

### 💰 VIP Customer Identification  
- A small group of **high-spending customers** contributes significantly to revenue.  
- The **top 10 customers**, led by *Eleanor Hunt*, have been identified.  
- This creates opportunities for **targeted marketing** and **loyalty programs**.  

### 🏢 Operational Disparities & Trends  
- **Store 1** outperforms **Store 2** with nearly **20% more customers**.  
- Suggests investigating factors such as **location, service quality, or inventory**.  
- A **seasonal trend** was observed, with rental activity **peaking in July and August**.  

### 🎬 Strategic Inventory & Pricing  
- Inventory is **well-balanced** across most film categories, serving a diverse audience.  
- A **tiered pricing model** exists, with different rental rates within the same category.  
- This allows the business to maximize revenue from **premium or high-demand films**.  

### 📊 Data Anomaly Detected  
- Time-series analysis revealed an **unusually low number of rentals in February 2006**.  
- This suggests a potential **data completeness issue** that requires further investigation.  

---

## 🛠️ Technical Stack  

- **Language:** Python, SQL  
- **Database:** PostgreSQL  

**Python Libraries Used:**  
- `pandas` → Data manipulation & analysis  
- `SQLAlchemy` → Database connection & query execution  
- `psycopg2` → PostgreSQL adapter for Python  
- `matplotlib` & `seaborn` → Data visualization  

**Environment:**  
- Jupyter Notebook  

---
