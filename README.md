# Data Survey Dashboard - Power BI Project

This repository contains a Power BI project analyzing a survey of individuals working in the tech industry. The project includes data transformation, visualization, and interactive filtering to extract meaningful insights.

## 📂 Repository Structure

| File Name | Description |
|-----------|------------|
| `Data Survey Dashboard.pbix` | The Power BI dashboard file containing all transformations, relationships, and visualizations. |
| `Data Survey Dashboard.pdf` | A snapshot of the final dashboard for quick reference. |
| `Data Survey.xlsx` | The original dataset used for analysis. |

## 📊 Project Overview

### **Dataset:**
The dataset consists of survey responses from **630 individuals** in the tech industry, covering various aspects of their careers and experiences.

### **Key Insights:**
- Distribution of respondents by **country**
- **Favorite programming languages**
- **Work/life balance satisfaction** levels
- **Salary satisfaction**
- Perceived **difficulty of breaking into tech**
- **Average age** of survey respondents

### **Techniques Used:**
✅ **Power Query**: Data cleaning, column transformations, and handling missing values
✅ **Data Modeling**: Creating relationships and defining cardinality
✅ **DAX (Data Analysis Expressions)**: Custom calculations for insights
✅ **Interactive Filtering**: Country-based filtering for dynamic visual updates

### **Visualizations Included:**
📌 **Stacked Bar Chart** - Average salary vs. job title  
📌 **Stacked Column Chart** - Favorite programming language distribution  
📌 **Treemap** - Country-wise survey distribution (interactive filter)  
📌 **Gauges** - Work/life balance and salary satisfaction  
📌 **Pie Chart** - Difficulty of breaking into tech  

## 🔄 Data Transformation Steps
- **Removed blank columns** (e.g., browser and referrer columns)
- **Grouped ‘Other’ job titles** into a single category
- **Split columns by delimiter** for multi-response questions (e.g., favorite programming language)
- **Processed salary data**: Extracted numeric values, removed symbols, and calculated salary averages
- **Reformatted country and industry columns** for consistency
- **Applied visual adjustments**: Changed color theme, arranged visuals for clarity

## 🚀 How to Use This Repository
1. **Download the `Data Survey.xlsx` file** if you want to explore the raw data.
2. **Open the `Data Survey Dashboard.pbix` file** in Power BI to interact with the dashboard.
3. **View `Data Survey Dashboard.pdf`** for a quick look at the final dashboard.

---

### 🎯 Learning Outcome
This project helped me enhance my Power BI skills, particularly in **data cleaning, visualization, DAX calculations, and interactive filtering**. By working through challenges like handling multi-value responses and cleaning salary data, I deepened my understanding of real-world data analysis.

💡 **Feel free to explore this project and use it as a reference for your own Power BI work!**

📩 **Got questions or suggestions? Reach out!**
