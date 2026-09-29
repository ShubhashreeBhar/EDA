# 🛒 Full Cart Store Annual Report 2022 — E-Commerce Sales EDA

An end-to-end Exploratory Data Analysis (EDA) on the 2022 sales performance of Full Cart Store. This project integrates an interactive Excel business dashboard powered by dynamic Pivot Tables and Slicers with an automated Python data processing pipeline.

---

## 📊 Executive Dashboard

![Full Cart Store Annual Report 2022](dashboard.png)

---

## 📌 Key Business Metrics (KPIs)

* **Top Selling Category**: **Set** (Total Revenue: **₹10,507,546**)
* **Primary Customer Base**: **Women (64%)**, predominantly **Adults (34.98%)**
* **Top Revenue Market**: **Maharashtra (₹3,001,779)**
* **Dominant Sales Channel**: **Amazon (35%)**
* **Fulfillment Rate**: **92% Delivered**

---

## 📑 Excel Pivot Tables Summary

### 1. Order vs. Sales Performance by Month (`DATA ANALYSIS-PIVOT-Q1`)
*Monthly trend analyzing total sales revenue against order volume.*

| Month | Order Trend (Count) | Sales Revenue (INR) | Seasonality Highlight |
| :--- | :---: | :---: | :--- |
| **January** | ~2,700 | ~₹1.80M | Solid start to Q1 |
| **February** | ~2,750 | ~₹1.87M | Steady growth |
| **March** | **~2,820** | **~₹1.92M** | **Peak revenue & order volume** |
| **April** | ~2,600 | ~₹1.78M | Post-Q1 correction |
| **May** | ~2,570 | ~₹1.74M | Mid-year plateau |
| **June** | ~2,550 | ~₹1.70M | Stable volume |
| **July** | ~2,540 | ~₹1.73M | Mid-year sales |
| **August** | ~2,620 | ~₹1.77M | Festive season pickup |
| **September** | ~2,420 | ~₹1.65M | Transition month |
| **October** | ~2,380 | ~₹1.62M | Pre-winter dip |
| **November** | ~2,330 | ~₹1.61M | Year-end drop |
| **December** | ~2,350 | ~₹1.62M | Year-end close |

---

### 2. Sales Share by Gender (`DATA ANALYSIS-PIVOT-Q2`)
*Revenue split between Men and Women.*

| Gender | Revenue Share (%) | Business Impact |
| :--- | :---: | :--- |
| **Women** | **64%** | Primary buyer segment driving store growth |
| **Men** | **36%** | Secondary consumer tier |
| **Total** | **100%** | |

---

### 3. Order Fulfillment Status (`DATA ANALYSIS-PIVOT-Q3`)
*Delivery success and logistical operational efficiency.*

| Fulfillment Status | Percentage (%) | Logistics Status |
| :--- | :---: | :--- |
| **Delivered** | **92%** | Optimal operational efficiency |
| **Cancelled** | **3%** | Customer cancellation before dispatch |
| **Returned** | **3%** | Reverse logistics / sizing returns |
| **Refunded** | **2%** | Disputed or failed fulfillments |


---

### 4. Sales: Top 10 States (`DATA ANALYSIS-PIVOT-Q4`)
*Geographical concentration of total sales revenue.*

| Rank | State | Total Revenue (INR) | Market Share Standing |
| :---: | :--- | :---: | :--- |
| 1 | **Maharashtra** | **₹3,001,779** | Highest revenue contributor |
| 2 | **Karnataka** | **₹2,645,078** | Key South India tier-1 hub |
| 3 | **Uttar Pradesh** | **₹2,104,133** | Largest Northern customer base |
| 4 | **Telangana** | **₹1,718,226** | Strong tech metro demand |
| 5 | **Tamil Nadu** | **₹1,678,212** | Core southern retail market |
| 6 | **Delhi** | **₹1,264,734** | High-density urban purchasing |
| 7 | **Kerala** | **₹1,008,176** | Consistent southern market |
| 8 | **West Bengal** | **₹921,202** | Top Eastern market |
| 9 | **Andhra Pradesh** | **₹910,862** | Developing customer hub |
| 10 | **Haryana** | **₹812,063** | NCR satellite demand |

---

### 5. Orders: Age Group vs. Gender (`DATA ANALYSIS-PIVOT-Q5`)
*Demographic matrix identifying high-converting age brackets across genders.*

| Demographic Segment | Gender | Order Share (%) | Key Takeaway |
| :--- | :--- | :---: | :--- |
| **Adult** | Women | **34.98%** | **Highest converting customer segment** |
| **Adult** | Men | **15.66%** | Core male buyer bracket |
| **Teenager** | Women | **21.13%** | Second-largest female consumer cohort |
| **Teenager** | Men | **9.20%** | Young male demographic |
| **Senior** | Women | **13.31%** | Active mature shopping segment |
| **Senior** | Men | **5.72%** | Smallest contributing group |

---

### 6. Orders by Sales Channels (`DATA ANALYSIS-PIVOT-Q6`)
*Marketplace distribution of incoming order volume.*

| Marketplace Channel | Order Volume Share (%) | Strategic Priority |
| :--- | :---: | :--- |
| **Amazon** | **35%** | Primary marketplace partner |
| **Myntra** | **23%** | Strongest fashion channel |
| **Flipkart** | **22%** | Major retail partner |
| **Ajio** | **6%** | Growing trendy apparel reach |
| **Meesho** | **5%** | Value/Tier-2/3 market presence |
| **Nalli** | **5%** | Ethnic apparel niche |
| **Others** | **4%** | Direct and miscellaneous web traffic |
---

## 💡 Strategic Business Insights & Recommendations

1. **Target Persona**: Women aged 21–50 (**Adult Women at ~35%**) form the commercial engine of the brand. Product catalog expansions, sizing variations, and lifestyle campaigns should cater directly to them.
2. **Product Focus**: The **Set** category is the undisputed top revenue generator (**₹10.5M+**). Bundled set promotions and new colorways will yield higher returns than single separates.
3. **Channel Strategy**: **Amazon, Myntra, and Flipkart collectively generate 80% of all orders**. Ad budgets, lightning deals, and inventory buffers must be concentrated on these three channels.
4. **Geographic Localization**: **Maharashtra, Karnataka, and Uttar Pradesh** generate the bulk of nationwide revenue. Targeted local language ads and regional warehouse fulfillment will decrease delivery lead times and reverse logistics costs.
5. **Logistics Health**: Maintaining a **92% delivery success rate** is robust; monitoring reasons for the 3% return rate (particularly around size/fit) can unlock further margins.

---

## 🛠️ Repository Architecture

```text
├── EXCEL_PROJECT (1).xlsx          # Master Excel workbook with raw data, Pivot sheets (Q1-Q6), and REPORTFULL
├── ecommerce_excel_eda.py           # Automated Python EDA and data processing script
├── dashboard.png                    # High-resolution screenshot of the REPORTFULL Excel dashboard
├── README.md                        # Project documentation and complete Pivot Table breakdowns
├── visualizations/                  # 12 automated Seaborn & Matplotlib analytical figures
└── eda_summary_tables/              # Exported CSV data summaries for business reporting