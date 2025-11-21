# 🍕 Domino’s Sales & Price Analytics Dashboard – Power BI

![Domino's Logo](Dominos.png)

A fully interactive Power BI dashboard built to analyze Domino’s stock performance, opening price trends, monthly trading volume, and key financial metrics using DAX measures and Power Query transformations.

---

## 📊 Project Overview
This dashboard delivers a detailed view of Domino’s financial performance with insights into:

- Price movement patterns  
- Volume traded per month  
- Highest/lowest price points  
- Daily opening and closing trends  
- Price change over time  

It is designed for analysts, students, and businesses wanting a clean and intuitive financial dashboard.

---

## 🧩 Key Features

### 🔹 **KPIs Included**
- **Highest Price:** 548.72  
- **Lowest Price:** 257.61  
- **Highest Opening Price:** 541.99  
- **Lowest Closing Price:** 255.70  
- **Total Volume Traded:** 178B  
- **Average Volume:** 353.31M  

---

### 📈 **Visualizations Used**
- Opening Price Trend Line Chart  
- Price Change Analysis  
- Volume by Month Column Chart  
- KPI Cards for High/Low Prices  
- Total Volume Summary  

---

## 🖼️ Dashboard Preview

### **📌 Preview (PDF Screenshot)**  
*(This will show directly on GitHub)*  
![Dashboard Preview](Dominos.png)

---

## 📂 Project Files Included

| File | Description |
|------|-------------|
| `Dominos.pbip` | Power BI project file |
| `Dominos.pdf` | Exported PDF of complete dashboard |
| `Dominos.png` | Preview image for README & GitHub |

---

## 🔧 Tools Used
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Data Modeling**
- **Data Visualization Techniques**

---

## 🔢 Sample DAX Measures

```DAX
Total Volume = SUM(Data[Volume])

Highest Price = MAX(Data[High])

Lowest Price = MIN(Data[Low])

Price Change = Data[Close] - Data[Open]

Average Volume = AVERAGE(Data[Volume])
