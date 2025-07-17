# 📊 Black Friday Sales Analysis

---

## 🎯 Objective
This project analyzes Black Friday retail transactions to uncover key patterns in customer behavior—across age, marital status, and product categories—with the goal of delivering data-driven recommendations that boost future revenue and retention.

---

## 🛠️ Tools & Tech
- **PostgreSQL (via DBeaver)**: Cleaned, normalized, and analyzed 550K+ transaction records.
- **Python (Google Colab)**: Performed exploratory data analysis using Pandas, Seaborn, and Matplotlib.
- **Tableau**: Built a single interactive dashboard for stakeholders to explore trends and metrics.
- **GitHub**: Hosted full documentation, code, and visual assets.

---

## 📈 Methodology
1. **Data Preparation**  
   - Loaded raw datasets into PostgreSQL, addressed nulls, standardized column names, and created a fact table.

2. **SQL Analysis**  
   - Executed business-driven queries to assess:
     - Revenue per product category
     - Purchase quantity by marital status and city tier
     - Spending patterns across age groups

3. **QA & Validation**  
   - Exported query results into Google Colab Python for sanity checks and cross-validation.

4. **Dashboard Development**  
   - Assembled an interactive Tableau dashboard combining all analyses.
   - Filters enable dynamic segmentation by age, gender, marital status, and city tier.

---

## 🔎 Key Insights
- **👑 Top Category:** Product Category 1 earned $22.7M — highest revenue, though average spend per user was modest compared to niche categories.
- **👫 Marital Patterns:** Unmarried customers purchase more items than married ones across city tiers, signaling untapped marketing potential.
- **🎯 Age Trends:** Individuals aged 26–35 generated $51.31M in spending, marking them as the most valuable segment; the 51–55 group had the highest spend *per purchase*.

---

## ✅ Recommendations
1. **Target 26–35 Age Group** with tailored campaigns, offers, and email retargeting.
2. **Upsell in Category 1** by setting up bundle or premium versions to increase average order value.
3. **Market to Unmarried Users** with single-focused promotions—especially in City Tier B.

---

## 📊 Dashboard
[Explore the full interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/miguel.negron/viz/Black__Friday_Sales_Dataset/Dashboard1)

---

## 📂 Repository Contents
- `sql/` → SQL scripts (data cleaning & analytics queries)
- `colab/` → Python notebook with EDA and visualizations
- `dashboard/` → Tableau workbook file
- `data/` → Raw and processed CSV files
- `images/` → Charts and dashboard screenshots for quick preview
- `README.md` → You're reading the project overview now!

---

## 🚀 Next Steps (Optional Stretch Goals)
- Set up an automated ETL pipeline using Google Colab + Google Drive/Snowflake to refresh the data and dashboard monthly.

---

## 📫 Connect with Me
- **LinkedIn**: [miguel-negron-garcia-3a6b001b9](https://www.linkedin.com/in/miguel-negron-garcia-3a6b001b9/)  
- **GitHub**: [github.com/MiguelNegron1](https://github.com/MiguelNegron1)

---

### 📌 Dataset
Original source: [Kaggle Black Friday Sales Dataset]([https://www.kaggle.com/datasets/sdolezel/black-friday](https://www.kaggle.com/datasets/rajeshrampure/black-friday-sale))
