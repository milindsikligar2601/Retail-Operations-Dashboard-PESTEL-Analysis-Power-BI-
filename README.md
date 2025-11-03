---

## 📊 Project Overview

This project develops a **Power BI dashboard** based on Tableau’s **Sample Superstore** dataset to analyze U.S. retail performance through a **PESTEL framework** (Political, Economic, Social, Technological, Environmental, Legal).  
The analysis provides insights into operational efficiency, sales performance, customer behavior, and logistics optimization across different U.S. regions.

---

## 🧾 Dataset Description

**Dataset:** Tableau Sample Superstore  
**Records:** 9,994 order-level entries (2014–2017)  
**Format:** Microsoft Excel (`Sample - Superstore.xls`)  
**Primary Table Used:** Orders  

### Key Attributes:
| Field | Description |
|-------|--------------|
| Order Date / Ship Date | Used for delivery time and trend analysis |
| State / Region | Enables regional and political comparisons |
| Category / Sub-Category | Product-level analysis |
| Customer ID / Segment | Social segmentation and customer profiling |
| Sales / Profit / Quantity / Discount | Economic performance metrics |
| Ship Mode | Evaluates technological and logistical efficiency |

---

## 🧹 Data Preparation

To enable meaningful PESTEL analysis, several preprocessing and transformation steps were conducted:
- Created **Profit Margin = Profit / Sales**
- Calculated **Delivery Time = Ship Date – Order Date**
- Extracted **Month, Quarter, and Year** for temporal insights
- Removed redundant fields: `Row ID`, `Postal Code`, `Product Name`, `Country`
- Cleaned null values and standardized categorical data
- Converted financial and percentage values into consistent decimal formats

---

## ⚙️ Analytical Framework — PESTEL

| Factor | Focus Area |
|--------|-------------|
| **Political** | State-level delivery patterns and logistics regulations |
| **Economic** | Sales, profit margins, discounting strategies |
| **Social** | Customer segments and preferences |
| **Technological** | Shipping methods and delivery optimization |
| **Environmental** | Product type and shipment frequency impact |
| **Legal** | Return patterns and policy implications |

---

## 📈 Dashboard Visuals & Insights

### 💡 Key Metrics
- **Total Customers:** 793  
- **Total Sales:** $2.30M  
- **Average Profit:** $28.66  
- **Average Discount:** 15.62%  
- **Average Delivery Time:** 3.96 days  
- **Total Orders Returned:** 296 (~13%)  

---

### 🔹 Major Visualizations

1. **Profit Margin vs. Sales (Scatter Plot)**  
   → Many transactions show low or negative margins, especially at low sales volumes.  
2. **Average Sales Over Time (Line Chart)**  
   → Sales remain stable with mild seasonality (2014–2017).  
3. **Average Delivery Time by State (Map)**  
   → Longer delivery times in central and rural areas.  
4. **Customers by Region & Ship Mode (Bar Chart)**  
   → West region leads; Standard Class shipping dominates.  
5. **Orders by Ship Mode (Donut Chart)**  
   → Standard Class: 59.7%, Second Class: 19.5%, First Class: 15.4%, Same Day: 5.3%.  
6. **Profit by Sub-Category (Waterfall)**  
   → Copiers and Phones are top contributors; Tables and Bookcases show losses.  
7. **Total Orders by Region & Category (Matrix)**  
   → Office Supplies lead overall; West region dominates in order volume.  
8. **Sales by Category (Sankey Chart)**  
   → Technology drives highest revenue despite fewer orders.  

---

## 🔍 Key Findings

- **High Discounting (15.6%)** is reducing profit margins.  
- **13% return rate** indicates potential quality or logistics issues.  
- **Standard shipping** is most used but has the **longest delivery time (~5 days)**.  
- **Same Day and First-Class** shipping are underutilized — opportunity for premium upselling.  
- **Central region** underperforms (low profit, long delivery).  
- **West and East regions** show highest profitability and operational efficiency.  
- **Technology category** has high revenue but inconsistent profitability.  
- **Consumer segment (63%)** dominates sales volume — opportunity to target Corporate and Home Office segments.  

---

## 🧭 PESTEL-Based Recommendations

| Factor | Recommendation |
|--------|----------------|
| **Political** | Partner with regional carriers to improve delivery in central states and ensure logistics compliance. |
| **Economic** | Focus marketing on high-margin categories (Copiers, Binders). Reassess low-performing products (Tables, Bookcases). |
| **Social** | Retain strong consumer focus but expand into Home Office segment through targeted promotions. |
| **Technological** | Adopt AI-based route optimization and real-time shipment tracking. |
| **Environmental** | Implement eco-friendly shipping (bulk delivery, recyclable packaging). |
| **Legal** | Review return policy transparency to reduce compliance risks from 296 returned orders. |

---

## 🧠 Conclusion

The dashboard highlights that:
- **High sales do not guarantee high profit** — pricing and discount policies need review.  
- **Delivery inefficiencies** in the central region impact satisfaction and cost.  
- **Standard Class** dominates due to cost sensitivity, but exploring **premium delivery** options could improve brand value.  
- **Regional disparity** suggests untapped opportunities in central and southern markets.  

---

## 🧰 Tools & Technologies

- **Power BI:** Dashboard creation and visualization  
- **Excel:** Data cleaning and transformation  
- **DAX & Calculated Columns:** Derived metrics (profit margin, delivery time)  
- **PESTEL Framework:** Strategic interpretation of insights  

---

## 📂 Repository Contents

| File | Description |
|------|--------------|
| `Final Project (1).pbix` | Power BI report containing dashboards and visuals |
| `Case Study 2 - Dashboard.pdf` | Project documentation and insights summary |
| `README.md` | Documentation file (this file) |

---

## 🎓 Learning Outcomes

- Build interactive dashboards integrating business frameworks (PESTEL).  
- Analyze operational and customer metrics using visual analytics.  
- Apply data-driven reasoning to identify inefficiencies and opportunities.  
- Translate analytics into strategic recommendations.
