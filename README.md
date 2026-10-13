# DA-redmi-
# 📱 Descriptive Analytics Report: Redmi Smartphones

> A descriptive analytics study of Redmi consumer behaviour in India, built on a **simulated** survey dataset of 850 respondents. It covers demographics, purchase trends, model preference, decision factors, channels, brand awareness, competitive positioning, satisfaction, regional demand, price sensitivity and repurchase intention.

![Type](https://img.shields.io/badge/Type-Descriptive%20Analytics-orange)
![Domain](https://img.shields.io/badge/Domain-Consumer%20Electronics-blue)
![Data](https://img.shields.io/badge/Data-Simulated-lightgrey)
![Respondents](https://img.shields.io/badge/Respondents-850-green)
![Period](https://img.shields.io/badge/Period-Sep%202025%20--%20Aug%202026-yellow)

---

## 👤 Author

| | |
|---|---|
| **Name** | Omkar Yadav |
| **Roll No.** | 1250258301 |
| **Section** | DS24 |
| **Report Date** | August 2026 |

---

## 📑 Table of Contents

1. [Overview](#-overview)
2. [Important Disclaimer](#%EF%B8%8F-important-disclaimer)
3. [Business Objectives](#-business-objectives)
4. [Dataset Description](#-dataset-description)
5. [Analytics Pipeline at Real Scale](#-analytics-pipeline-at-real-scale)
6. [Methodology](#-methodology)
7. [Key Findings](#-key-findings)
8. [Headline KPIs](#-headline-kpis)
9. [Recommendations](#-recommendations)
10. [From Descriptive to Predictive](#-from-descriptive-to-predictive)
11. [Limitations and Data Notes](#-limitations-and-data-notes)
12. [Report Structure](#-report-structure)
13. [Suggested Repository Structure](#-suggested-repository-structure)
14. [Tech Stack](#-tech-stack)
15. [Glossary](#-glossary)
16. [Keywords](#-keywords)
17. [License and Usage](#-license-and-usage)

---

## 🔍 Overview

This project builds a **descriptive analytics layer** over Redmi's consumer-survey data. Descriptive analytics answers one question: *what happened?* The report summarises who buys Redmi phones, why they choose them, where they buy, how satisfied they are afterwards, and whether they will come back.

The analysis uses **850 usable survey responses** collected over a **30-day fieldwork window**. The responses span **6 regional zones** and **8 Redmi model families**, with a **12-month purchase-recall window (Sep 2025 – Aug 2026)**.

---

## ⚠️ Important Disclaimer

The dataset is **simulated**. It was reconstructed to illustrate typical Indian budget and mid-range smartphone buying behaviour.

- Findings are **illustrative only**.
- Figures **must not be quoted as verified Xiaomi or Redmi sales data**.
- The project is intended for **learning and portfolio purposes**.

---

## 🎯 Business Objectives

The report answers seven recurring business questions:

| # | Question | Report Section |
|---|----------|----------------|
| 1 | Who is buying Redmi smartphones, and what does their demographic profile look like? | 3 |
| 2 | Which factors most influence the choice of Redmi over a competing brand? | 6 |
| 3 | Which Redmi models are most preferred, and where and how are they purchased? | 4, 5, 7 |
| 4 | How aware are consumers of Redmi, and through which channels? | 8 |
| 5 | How does Redmi compare to competing brands on the attributes that matter most? | 9 |
| 6 | How satisfied are buyers after purchase, and where is satisfaction slipping? | 10 |
| 7 | Will buyers come back? What do repurchase intention and loyalty look like? | 13 |

---

## 📊 Dataset Description

| Attribute | Detail |
|-----------|--------|
| **Nature** | Simulated consumer-survey dataset |
| **Usable responses** | 850 |
| **Fieldwork window** | 30 days |
| **Purchase-recall window** | 12 months (Sep 2025 – Aug 2026) |
| **Regional zones** | 6 (North, South, East, West, Central, North-East) |
| **Model families** | 8 |
| **Decision factors rated** | 10 (scale of 1–5) |
| **Satisfaction scale** | 1–5, asked at least one month after purchase |

### Models covered

Redmi Note 14 Pro+, Redmi 15, Redmi Note 14, Redmi 14C, Redmi Note 13 Pro, Redmi A5, Redmi Note 14 Pro, Redmi 13C 5G.

### Competing brands in the consideration set

Samsung, Realme, Vivo, Poco, Motorola, and others.

### Budget tiers used

| Tier | Price Band |
|------|-----------|
| Entry | Under ₹10,000 |
| Value | ₹10,000 – 15,000 |
| Core Note-series | ₹15,000 – 20,000 |
| Upper-mid | ₹20,000 – 25,000 |
| Premium Redmi (e.g. Note Pro+ variants) | Above ₹25,000 |

---

## 🏗️ Analytics Pipeline at Real Scale

Turning survey responses into a reusable analytics layer is a **data-pipeline problem before it is a reporting problem**. A realistic production setup would look like this:

| Layer | Purpose | Typical Tools |
|-------|---------|---------------|
| **Investigation** | Design and validate the questionnaire structure | Google Forms / SurveyMonkey |
| **Collection** | Field the structured survey across regional zones | Online and in-person data collection |
| **Storage** | Retain raw and cleaned response data | CSV / Excel exports |
| **Aggregation** | Compute demographic, decision-factor and satisfaction KPIs | Python (pandas) |
| **Report** | Present analysis, charts and recommendations | Matplotlib / MS Word |

In a live setup, results would feed a dashboard that refreshes each time a new response wave arrives.

---

## 🧪 Methodology

- **Survey-based descriptive analysis.** Frequencies, percentages and mean scores are used throughout.
- **Likert-style scoring.** Decision factors, brand perception and satisfaction are rated on 1–5 scales.
- **Multi-select questions.** Awareness-channel recall allowed respondents to pick every channel they remembered, so percentages sum to more than 100%.
- **Cross-tabulation.** Budget preference is cross-tabulated against age group.
- **Time-series view.** Purchases are counted per month across the 12-month recall window.
- **Comparative perception analysis.** Redmi is compared with Samsung and Realme across six attributes.
- **Visualisation.** Bar, donut, line and stacked-bar charts (Figures 1–15).

---

## 💡 Key Findings

### 1. Respondent Demographics

- **70%** of respondents are aged 18–34 (18–24: 41%, 25–34: 29%).
- **58%** are male, **39%** female, **3%** prefer not to say.
- **37%** are students, followed by privately salaried professionals (29%). Together they make up about two-thirds of the sample.
- **56%** have a monthly household income under ₹30,000.
- **Takeaway:** the typical buyer is young, budget-conscious and often purchasing independently for the first time. This is the segment Redmi's pricing and marketing target.

### 2. Purchase Trends

- **Peak month:** December (794 respondents), aligned with year-end sale events on Amazon and Flipkart.
- **Trough month:** February

- # 📊 Business Intelligence Reporting Practicals

A collection of hands-on reporting and data visualization practicals covering dashboard design, list reports, cross-filtering, and chart creation using sales data. Each practical is exported as a PDF report and documented below.

---

## 📑 Table of Contents

1. [Overview](#-overview)
2. [Repository Structure](#-repository-structure)
3. [Tools & Technologies](#-tools--technologies)
4. [Dataset Description](#-dataset-description)
5. [Practical 1 – Pie Chart Dashboard with Filter Panels](#-practical-1--pie-chart-dashboard-with-filter-panels)
6. [Practical 2 – List Reports with Clustered Column Chart](#-practical-2--list-reports-with-clustered-column-chart)
7. [Practical 3 – Filtered Subset Reports](#-practical-3--filtered-subset-reports)
8. [Practical 4](#-practical-4)
9. [Key Observations & Insights](#-key-observations--insights)
10. [Known Issues & Possible Improvements](#-known-issues--possible-improvements)
11. [How to View the Reports](#-how-to-view-the-reports)
12. [Learning Outcomes](#-learning-outcomes)
13. [Author](#-author)
14. [License](#-license)

---

## 🔎 Overview

This repository contains four reporting practicals built around retail sales data. The practicals progress from a single visual-heavy dashboard to multi-component reports that combine tabular data with charts, and then to filtered subsets of those reports.

Skills demonstrated:

- Building dashboards with themed layouts (headers, side panels, footers)
- Creating pie charts and clustered column (bar) charts
- Designing list/table reports with formatted currency columns
- Using categorical filters (Region, Payment Method, Product Category)
- Adding report metadata such as date, page number and time stamps

---

## 📁 Repository Structure

```
.
├── Prac_1.pdf      # Pie chart dashboard with four filter-panel pages
├── PRAC_2.pdf      # Full list reports + clustered column chart
├── PRAC_3.pdf      # Filtered subset of the Practical 2 reports
├── PRAC_4.pdf      # Practical 4 report
└── README.md       # Project documentation
```

---

## 🛠 Tools & Technologies

| Category            | Details                                              |
|---------------------|------------------------------------------------------|
| Reporting tool      | IBM Cognos Analytics (report/dashboard authoring)    |
| Output format       | PDF export                                           |
| Visualizations      | Pie chart, clustered column chart, list tables       |
| Data currency       | Indian Rupee (₹) for Practicals 2 and 3              |
| Report generated on | 8–9 October 2026                                     |

> Update this table if you used a different tool.

---

## 🗂 Dataset Description

The practicals use sales transaction data with the following fields.

### Practical 1 fields

| Field          | Description                                          | Example Values                               |
|----------------|------------------------------------------------------|----------------------------------------------|
| Date           | Transaction date (Jan–Mar 2024)                      | 1 Jan 2024, 3 Jan 2024, 2 Mar 2024           |
| Region         | Geographic region of the sale                        | North America, Europe, Asia                  |
| Payment Method | How the customer paid                                | Credit Card, PayPal, Debit Card              |
| Units Sold     | Number of units in a transaction                     | 180, 105, 145, 88                            |
| Unit Price     | Price per unit                                       | 353.87225, 190.90425, 67.5365, 261.284       |
| Sales value    | Value plotted on the pie chart                       | 3,899.99, 2,399, 1,895, 1,599.99, 1,499.98   |

### Practical 2 and 3 fields

| Field            | Description                            | Example Values                                  |
|------------------|----------------------------------------|-------------------------------------------------|
| Sales Amount     | Transaction value in Indian Rupees (₹) | ₹18,628.00, ₹22,793.00, ₹47,380.00              |
| Product Category | Category of the product sold           | Electronics, Furniture, Grocery, Clothing       |
| Store Name       | Individual store identifier            | East Store A, North Store B, South Store A      |
| Region           | Store region                           | North, South, East, West                        |
| Quantity         | Units sold (used in the chart)         | See chart data below                            |

---

## 🥧 Practical 1 – Pie Chart Dashboard with Filter Panels

**File:** `Prac_1.pdf` (4 pages)

### Objective
Design a themed dashboard that visualizes sales across dates using a pie chart, with a side panel listing a different dimension or measure on each page.

### Layout
- **Theme:** Light green background with dark green header blocks and a bright green top accent bar
- **Left panel:** Dark green banner area with a list/filter table below it
- **Main panel:** Dark green title banner with a pie chart beneath it
- **Footer:** Report date (9 Oct 2026), page number, and time stamp (00:38:04)

### Pages

| Page | Left Panel Column | Values Shown                                      |
|------|-------------------|---------------------------------------------------|
| 1    | Region            | North America, Europe, Asia, Asia                 |
| 2    | Payment Method    | Credit Card, PayPal, Debit Card, Credit Card      |
| 3    | Units Sold        | 180, 105, 145, 88                                 |
| 4    | Unit Price        | 353.87225, 190.90425, 67.5365, 261.284            |

### Chart details
- **Type:** Pie chart
- **Category (legend):** Date, running from 1 Jan 2024 to 2 Mar 2024. The legend is truncated with "..." because there are so many dates.
- **Data labels:** The largest slices are labelled 3,899.99, 2,399, 1,895, 1,599.99 and 1,499.98.

### Notes
- The pie chart is identical on all four pages, so the left-panel lists are not filtering the chart.
- With roughly 60 or more date slices, small slices are hard to read.

---

## 📈 Practical 2 – List Reports with Clustered Column Chart

**File:** `PRAC_2.pdf` (2 pages)

### Objective
Combine list (table) reports with a clustered column chart showing quantity sold by region and product category.

### Page 1 – Sales Amount by Product Category

| Sales Amount | Product Category |
|--------------|------------------|
| ₹18,628.00   | Electronics      |
| ₹22,793.00   | Furniture        |
| ₹15,345.00   | Grocery          |
| ₹24,411.00   | Clothing         |
| ₹47,380.00   | Furniture        |
| ₹10,117.00   | Clothing         |
| ₹11,126.00   | Furniture        |
| ₹7,814.00    | Clothing         |
| ₹17,955.00   | Grocery          |
| ₹26,249.00   | Furniture        |
| ₹29,305.00   | Electronics      |
| ₹8,647.00    | Clothing         |
| ₹28,756.00   | Electronics      |
| ₹5,032.00    | Clothing         |
| ₹17,070.00   | Electronics      |
| ₹26,223.00   | Furniture        |
| ₹32,282.00   | Grocery          |
| ₹15,066.00   | Clothing         |
| ₹ (continues on next page) | Electronics |

### Page 2 – Stores by Region

| Store Name    | Region |
|---------------|--------|
| East Store A  | East   |
| East Store B  | East   |
| East Store C  | East   |
| North Store A | North  |
| North Store B | North  |
| North Store C | North  |
| South Store A | South  |

### Chart – Quantity by Region and Product Category

- **Type:** Clustered column chart
- **X-axis:** Region (North, South, West, East)
- **Y-axis:** Quantity (0–160)
- **Series:** Product Category (Furniture, Clothing, Grocery, Electronics)

Approximate values read from the chart:

| Region | Furniture | Clothing | Grocery | Electronics |
|--------|-----------|----------|---------|-------------|
| North  | ~61       | ~50      | ~32     | ~70         |
| South  | ~6        | ~92      | ~46     | ~141        |
| West   | ~28       | ~44      | ~45     | ~36         |
| East   | ~65       | ~6       | ~9      | ~24         |

Report generated: **08-Oct-26, 4:09:15 AM**

---

## 🔍 Practical 3 – Filtered Subset Reports

**File:** `PRAC_3.pdf` (2 pages)

### Objective
Reproduce the Practical 2 report with the list tables limited to a subset of rows, while the chart stays the same.

### Page 1 – Sales Amount by Product Category (subset)

| Sales Amount | Product Category |
|--------------|------------------|
| ₹7,814.00    | Clothing         |
| ₹17,955.00   | Grocery          |
| ₹26,249.00   | Furniture        |
| ₹29,305.00   | Electronics      |
| ₹8,647.00    | Clothing         |
| ₹28,756.00   | Electronics      |

### Page 2 – Stores by Region (subset)

| Store Name    | Region |
|---------------|--------|
| North Store A | North  |
| North Store B | North  |

### Chart
Same clustered column chart as Practical 2 (Quantity by Region, grouped by Product Category).

Report generated: **08-Oct-26, 4:12:04 AM**

> The six sales rows are a contiguous slice of the Practical 2 list. Document the exact filter or condition you applied here (for example a rank filter, range filter, or prompt).

---

## 🧪 Practical 4

**File:** `PRAC_4.pdf`

> ⚠️ **TODO:** Add the objective, steps, and output description for Practical 4.

Suggested sections:
- Objective
- Data fields used
- Visualizations / report components
- Key observations

---

## 💡 Key Observations & Insights

From the Practical 2 and 3 chart:

1. **Electronics in the South is the top performer**, at roughly 141 units, well ahead of every other region and category.
2. **The South is highly imbalanced.** Furniture sells only about 6 units there, against about 92 for Clothing.
3. **The East favors Furniture** (about 65 units), while Clothing and Grocery are very weak there (about 6 and 9).
4. **The West is the most balanced region**, with every category between about 28 and 45 units.
5. **The North is led by Electronics** (about 70), followed by Furniture (about 61).

From the Practical 2 sales table:

- The highest single sale shown is **₹47,380 (Furniture)**.
- The lowest shown is **₹5,032 (Clothing)**.
- Furniture and Electronics tend to have higher transaction values than Clothing and Grocery.

---

## ⚠️ Known Issues & Possible Improvements

| Area        | Issue                                                                 | Suggested Fix                                                         |
|-------------|-----------------------------------------------------------------------|-----------------------------------------------------------------------|
| Practical 1 | Pie chart has too many slices to read                                 | Use a bar or line chart for time series, or group dates by month      |
| Practical 1 | Chart does not change between pages                                   | Connect the left-panel filters to the chart                           |
| Practical 1 | Region list shows "Asia" twice                                        | Apply distinct values or aggregation                                  |
| Practical 1 | Dark green banners are empty                                          | Add report titles and descriptive text                                |
| Practical 2 | Rupee symbol wraps to a separate line in narrow columns               | Widen the Sales Amount column                                         |
| Practical 2 | Table cuts off at the page end (last row's amount is on the next page)| Adjust pagination or row heights                                      |
| Practical 2 | Store table has no relation to the chart or sales table               | Join stores and sales into one query                                  |
| Practical 3 | Filter logic is not documented                                        | Add the filter criteria as a report subtitle                          |
| All         | Tables and charts lack titles                                         | Add titles, axis labels and units                                     |

---

## ▶️ How to View the Reports

1. Clone or download this repository:
```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
```
2. Open any PDF in a PDF viewer, or click the file in GitHub to preview it in the browser.
3. To regenerate the reports, open the source in your reporting tool, connect the data source, and re-run and export to PDF.

---

## 🎓 Learning Outcomes

After completing these practicals you should be able to:

- Create and style multi-panel dashboards
- Choose the right chart for the data, and recognize when a chart is a poor fit
- Build list reports with currency formatting
- Build clustered column charts with a categorical series
- Apply filters to produce subset reports
- Export and distribute reports with metadata footers

---

## 👤 Author

**Name:** `<Your Name>`
**Course / Institution:** `<Course Name, Institution>`
**Contact:** `<Email or GitHub profile>`

---

## 📄 License

This project is for educational purposes. Add a license (for example MIT) if you want to allow reuse.
