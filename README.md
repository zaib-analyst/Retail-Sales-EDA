# 📊 Retail Sales Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on a retail sales dataset to evaluate transactional patterns, customer demographics, and revenue growth drivers. The primary goal is to transform raw sales data into actionable business intelligence using structured statistical and visualization techniques.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook / Anaconda

## 🔑 Key Features & Methodology
1. **Structural Audit & Summary Statistics:** Evaluated dataset dimensions (1,000 rows, 9 columns), confirmed 0 missing values/duplicates, and computed central tendencies (`mean`, `median`, `mode`, `std`).
2. **Time-Series Revenue Analysis:** Resampled sales transactions across monthly (`ME`) and quarterly (`QE`) intervals to identify seasonal revenue peaks and dips.
3. **Demographic Binning & Segmentation:** Grouped customer ages into discrete brackets (`Under 25`, `25-40`, `41-60`, `Over 60`) and analyzed transaction distribution across gender.
4. **Category & Correlation Analysis:** Aggregated revenue across product lines (`Electronics`, `Clothing`, `Beauty`) and constructed a Pearson correlation matrix heatmap to evaluate relationships between `Price per Unit`, `Quantity`, and `Total Amount`.
5. **Cross-Demographic Profiling:** Built multi-variable bar charts analyzing revenue distribution across age groups and product lines simultaneously.

## 📈 Key Findings & Insights
* **Primary Economic Driver:** Customers aged **41–60** generated the highest sales volume across all product lines.
* **Balanced Product Portfolio:** Revenue was evenly distributed across **Electronics** ($156.9K), **Clothing** ($155.5K), and **Beauty** ($143.5K).
* **Revenue Drivers:** `Total Amount` exhibited a strong positive correlation (0.85) with `Price per Unit`, indicating that higher-value items drive revenue more effectively than volume bundling.

## 💡 Strategic Recommendations
1. **Targeted Demographic Campaigns:** Allocate marketing expenditure toward middle-aged professionals (41–60) via personalized loyalty offers on high-end Electronics and Clothing.
2. **Cross-Category Bundling:** Bundle top-performing Electronics with Beauty/Clothing products to boost basket size among younger and senior customer segments.
3. **Seasonal Inventory Alignment:** Synchronize inventory stock levels with quarterly sales cycles to minimize stockouts during peak revenue windows.
