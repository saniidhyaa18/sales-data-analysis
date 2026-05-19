# 📊 Sales Data Analysis (EDA Project)

This project performs **Exploratory Data Analysis (EDA)** on a multi-year sales dataset to uncover trends in revenue, product performance, pricing patterns, and geographic performance.

---

# 🧰 Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Google Colab

---

# 📁 Dataset
**File:** Sales_data(EDA Exported).csv

Contains:
- Orders
- Revenue
- Cost
- Profit
- Product info
- Geographic info
- Sales channels
- Budget data

---

# 📊 EDA Analysis & Insights

---

# 1️⃣ Monthly Sales Trend (Time Series)

<img width="1403" height="360" alt="image" src="https://github.com/user-attachments/assets/d0e6eb29-77ef-4b43-8998-94d08ac6ee4b" />

### Insight
Revenue remains relatively stable between **$23M–$26M monthly**, showing consistent performance across years with small fluctuations.

---

# 2️⃣ Monthly Sales Seasonality (All Years Combined)

<img width="1300" height="387" alt="image" src="https://github.com/user-attachments/assets/204ebb85-5746-485f-b149-27373cb89680" />

### Insight
- January starts strong (~$99M)
- Dip occurs around **April (~$95M)**
- Peak months: **May & August (~$102M)**
- Stable plateau from September–December

Indicates **seasonal buying patterns**.

---

# 3️⃣ Top 10 Products by Revenue

<img width="888" height="386" alt="image" src="https://github.com/user-attachments/assets/529a3e3b-f121-4b50-88f2-27277a338cd6" />

### Insight
- Product 26 and 25 lead significantly (~$118M & $110M)
- Mid-tier cluster around **$68M–$75M**
- Bottom group shows similar performance (~$52M–$57M)

High revenue concentration among few products.

---

# 4️⃣ Top 10 Products by Average Profit Margin

<img width="887" height="389" alt="image" src="https://github.com/user-attachments/assets/3a7a95d5-d914-4543-bf30-06b509c698f2" />

### Insight
- Product 18 and 28 show highest profitability (~$8K margin)
- Most top products fall within **$7.4K–$8.3K range**
- Indicates relatively consistent margin structure

Opportunity to scale high-margin products.

---

# 5️⃣ Sales by Channel

<img width="478" height="485" alt="image" src="https://github.com/user-attachments/assets/27f9fe43-8328-4a70-a629-1f61aaafa066" />

### Insight
- Wholesale dominates (54%)
- Distributor contributes 31%
- Export accounts for 15%

Business heavily depends on wholesale channel.

---

# 6️⃣ Average Order Value Distribution

<img width="1187" height="390" alt="image" src="https://github.com/user-attachments/assets/2f6675bf-5d0a-4eae-a6c1-6239cbd314cb" />

### Insight
- Most orders fall between **$20K–$120K**
- Peak frequency around **$50K–$60K**
- Long tail reaching $400K+

Presence of high-value bulk orders.

---

# 7️⃣ Profit Margin % vs Unit Price

<img width="587" height="393" alt="image" src="https://github.com/user-attachments/assets/89b6a1ab-01d8-4ac6-bca7-0f719b90d1bc" />

### Insight
- Profit margin mostly ranges between **18%–60%**
- No strong correlation between price and margin
- Consistent pricing strategy across products

Margins remain stable across pricing tiers.

---

# 8️⃣ Unit Price Distribution per Product

<img width="1190" height="391" alt="image" src="https://github.com/user-attachments/assets/da894f0b-1922-4806-8302-362a091b9b56" />

### Insight
- Several products show price outliers above $6000
- Some products have low-end pricing anomalies (~$0–$100)
- Possible promotional or bundled pricing effects

Price consistency varies across products.

---

# 9️⃣ Total Sales by US Region

<img width="988" height="387" alt="image" src="https://github.com/user-attachments/assets/0aa32721-60d7-48a2-ab0f-afce50c1cdda" />

### Insight
- West leads (~$360M)
- South & Midwest strong (~$320M each)
- Northeast lowest (~$210M)

Western region is primary revenue driver.

---

# 🔟 Total Sales by State (Choropleth Map)

<img width="1398" height="521" alt="image" src="https://github.com/user-attachments/assets/02da0e45-dfa6-4c9d-bfe6-2e1e68e2e2a4" />

### Insight
- California highest performer (~$230M)
- Illinois and Florida follow
- Some states show low market penetration

Geographic growth opportunities identified.


---

# 1️⃣1️⃣ Top 10 States by Revenue and Order Count

<img width="1396" height="429" alt="image" src="https://github.com/user-attachments/assets/93349f17-e295-4187-af98-e71984c7bc29" />

### Insight
- States generating higher revenue also tend to have higher order counts.
- Strong positive relationship between demand volume and revenue contribution.
- Indicates consistent customer purchasing behavior in top-performing states.

Helps identify high-value geographic markets.

---

# 1️⃣2️⃣ Average Profit Margin by Channel

<img width="588" height="386" alt="image" src="https://github.com/user-attachments/assets/012f19ba-f8a2-4b08-9bf7-40f71d4ea397" />

### Insight
- Export channel shows highest margin (~37.93%)
- Distributor (~37.56%) and Wholesale (~37.09%) follow closely
- Margin difference across channels is minimal (<1%)

Indicates stable pricing strategy and cost efficiency across channels.

---

# 1️⃣3️⃣ Top and Bottom 10 Customers by Revenue

<img width="1400" height="363" alt="image" src="https://github.com/user-attachments/assets/ff25e638-a55a-40e4-9e1f-fe4977fc7656" />
<img width="1398" height="362" alt="image" src="https://github.com/user-attachments/assets/21646ffe-1c9f-44cc-a7da-05878678efbb" />


### Insight
- Top customers generate nearly **2x revenue** compared to bottom-tier customers.
- Revenue concentration indicates importance of retaining high-value customers.
- Bottom customers show potential for targeted marketing strategies.

Customer segmentation can improve revenue distribution.

---

# 1️⃣4️⃣ Customer Segmentation: Revenue vs Profit Margin

<img width="691" height="492" alt="image" src="https://github.com/user-attachments/assets/49538280-112e-42bf-93a4-2281bede8f0e" />

### Insight
- Most customers cluster within **$6M–$10M revenue range**
- Profit margins remain stable between **34%–40%**
- Larger customers do not show reduced profitability

Indicates scalable business model with stable margins.

---

# 1️⃣5️⃣ Correlation Heatmap of Numeric Features

<img width="564" height="389" alt="image" src="https://github.com/user-attachments/assets/30850b56-daa5-46f8-9cf6-184c35c9eae9" />

### Insight
- Revenue strongly correlates with profit (0.87)
- Unit price highly correlated with revenue (0.91)
- Cost strongly linked with revenue (0.85)
- Quantity shows weaker relationship with profit (0.30)

Pricing strategy has stronger impact than order volume.

---

# Dashboard Overview

<img width="1303" height="724" alt="image" src="https://github.com/user-attachments/assets/a5d0672c-c77a-43b5-9b19-871043dd6585" />
<img width="1301" height="714" alt="image" src="https://github.com/user-attachments/assets/edf0e004-8bd1-4d51-a17b-f986289be332" />
<img width="1299" height="722" alt="image" src="https://github.com/user-attachments/assets/21a86587-7e1c-452e-803b-fec582d4904a" />


---


# 🔎 Overall Key Insights

### Monthly Revenue Cycle
Revenue stays stable between **~$23M–$26.5M** across 2014–2017, with no consistent seasonal spikes. Sharpest drop (~$21.2M) occurs in early 2017, indicating possible one-time disruption.

### Channel Mix
Wholesale contributes **54%**, Distributor **31%**, Export **15%** — showing opportunity to scale international presence.

### Top Products (Revenue)
Product 26 leads with **$118M**, followed by Product 25 (**$110M**) and Product 13 (**$78M**). Mid-tier products contribute **$68M–$75M**, while lower performers range **$52M–$57M**.

### Profit Margins
Profit margins range between **18%–60%**, with no strong correlation to unit price. Consistent margin bands suggest standardized pricing strategy.

### Seasonal Volume
No strong monthly trend observed, though slight volume increase appears around **May–June**. Early 2017 dip (~$21.2M) may require investigation.

### Regional Performance
California leads with **~$230M revenue and 7500+ orders**. Illinois, Florida, Texas follow (~$85M–$110M revenue). NY and Indiana contribute **~$54M with 2000+ orders**.

---

# 💡 Recommendations

1. **Outlier Strategy**  
   Exclude or formalize bulk-order and promotional SKUs when calculating averages to avoid distorted insights.

2. **Margin Uplift Opportunity**  
   Apply pricing strategies from high-performing products to mid and low performers to improve margins.

3. **Export Growth Strategy**  
   Invest in international partnerships and export-focused marketing initiatives.

4. **Seasonal Planning**  
   Allocate marketing budget around **May–June peak** and investigate early 2017 dip.

5. **Dashboard Preparation**  
   Create aggregated tables for time series, channel mix, and product performance for Power BI dashboards.

---

