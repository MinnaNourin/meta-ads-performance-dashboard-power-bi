# 📊 Meta Ad Performance Dashboard

![PowerBI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Domain](https://img.shields.io/badge/Domain-Digital%20Marketing%20Analytics-1D4ED8?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Data%20Source-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![Platforms](https://img.shields.io/badge/Platforms-Facebook%20%7C%20Instagram-E1306C?style=for-the-badge&logo=instagram&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A comprehensive **Power BI dashboard** analyzing Meta (Facebook & Instagram) advertising campaign performance — covering engagement rates, audience demographics, ad type efficiency, campaign budgets, and cross-platform ROI.

---

## 📊 Dashboard Preview

### Ad Performance Dashboard
![Ad Performance](screenshots/dashboard1.png)

### Campaign Budget & Performance Analysis
![Campaign Budget Analysis](screenshots/dashboard2.png)

---

## 🔑 Key Metrics

| Metric | Value |
|---|---|
| Total Impressions | 340K |
| Total Clicks | 40K |
| Total Engagements | 60K |
| Click-Through Rate (CTR) | 11.79% |
| Engagement Rate | 17.71% |
| Conversion Rate | 5.07% |
| Purchase Rate | 0.60% |
| Total Budget | $2.5M |
| Avg Budget / Campaign | $50.7K |
| Total Purchases | 2K |

---

## 📁 Repository Structure

```
meta-ad-performance-dashboard/
│
├── Meta_Ad_Performance_dashboard.pbix      # Power BI dashboard file
├── Meta_Ad_Performance_Report.docx         # Detailed project report
├── screenshots/
│   ├── dashboard1.png                      # Ad Performance page
│   └── dashboard2.png                      # Campaign Budget Analysis page
├── LICENSE
└── README.md
```

---

## 📌 Dashboard Pages

### 1. Ad Performance Dashboard
- **Engagements by Gender** — Donut: Male 55.42% | Female 34.34% | Other 10.24%
- **Engagements by Age** — Bar chart: 25–34 is the top cohort (~22K engagements), followed by 18–24
- **Engagements by Country** — World bubble map showing global campaign reach across Europe, Asia & Americas
- **Analysis by Ad Type** — Matrix table comparing Stories, Image, Carousel & Video across impressions, CTR, conversions & engagements
- **Weekly Engagement Trend** — Stacked bar chart (weeks 20–30); stable performance across all ad types
- **Hourly Engagements Trend** — Stacked area chart showing consistent engagement activity throughout the day

### 2. Campaign Budget & Performance Analysis
- **Top Campaigns by Engagements** — Campaign_17_Launch leads (~2.3K), followed by Campaign_38_Q3 & Campaign_20_Winter
- **Budget vs Purchase Scatter** — Reveals that budget size alone doesn't predict purchases; targeting quality is the key differentiator
- **Campaign Performance by Platform** — Diverging bar: most campaigns perform better on Facebook; Campaign_33_Summer is an Instagram outlier
- **Cost Per Engagement (CPE)** — Campaign_41_Winter has the highest CPE (~100); Campaign_17_Launch is the most cost-efficient
- **Campaign Duration vs Engagements** — Scatter showing no strong duration-engagement correlation
- **Engagements by Ad Platform** — Facebook and Instagram show near-equal total engagement split

---

## 🔍 Key Insights

- 📈 **CTR vs Engagement Gap** — 11.79% CTR + 17.71% engagement rate indicates significant non-click brand interactions (likes, shares, comments)
- 🎯 **Ad Type Parity** — All four formats (Stories, Image, Carousel, Video) deliver nearly identical CTR (~11.7–11.9%) — diversification is safe
- 👥 **25–34 Age Dominance** — This cohort generates disproportionately high engagement and should anchor targeting strategy
- 💸 **Campaign_41_Winter Inefficiency** — Highest CPE with below-average results; needs creative/targeting review before further spend
- 🏆 **Campaign_17_Launch is the Benchmark** — Best combination of high engagement and low CPE across all campaigns
- 🛒 **Purchase Funnel Drop-off** — 5.07% conversion rate vs 0.60% purchase rate signals post-click landing page optimisation is needed

---

## 🎛️ Filters & Interactivity

Both pages support dynamic filtering by:
- **Platform** — Facebook / Instagram toggle
- **Ad Type** — All / Stories / Image / Carousel / Video
- **Target Interest** — Audience interest segments
- **Campaign** — Individual campaign selector
- **Date Range** — Slider + date picker (07-May-2025 to 06-Aug-2025)
- **Duration Days** — Campaign duration bracket filter

---

## 📂 Dataset

- **Source:** [Kaggle](https://www.kaggle.com/) — Meta Ad Performance Dataset
- **Note:** The raw dataset is not included due to file size. Download it from Kaggle and connect it to the Power BI file via **Transform Data > Data Source Settings**.
- **Date Range:** 07-May-2025 to 06-Aug-2025
- **Platforms:** Facebook & Instagram

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard creation & DAX measures |
| TomTom / OpenStreetMap | Geographic engagement map |
| DAX | CTR, Engagement Rate, Conversion Rate, CPE calculations |
| Kaggle | Data source |

---

## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone this repository
3. Open `Meta_Ad_Performance_dashboard.pbix`
4. Go to **Transform Data > Data Source Settings** to reconnect your local dataset if prompted

---

## 📄 Project Report

A detailed project report (`Meta_Ad_Performance_Report.docx`) is included, covering:
- Executive summary & all KPIs
- Full dashboard documentation for both pages
- Key insights & findings
- Actionable recommendations for campaign optimisation

---

## 💡 Recommendations

- Scale budget for Campaign_17_Launch and Campaign_38_Q3 — highest efficiency
- Audit Campaign_41_Winter creative and targeting to reduce CPE
- A/B test female-targeted creatives to improve gender engagement balance
- Optimise post-click landing pages to bridge the conversion-to-purchase gap
- Build dedicated Instagram-first creatives using Campaign_33_Summer as a model

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋 Author

> Feel free to connect or raise an issue if you have feedback on the dashboard!
