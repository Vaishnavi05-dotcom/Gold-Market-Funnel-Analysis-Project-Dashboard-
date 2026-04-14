# Gold Market Funnel Analysis Dashboard

An interactive, single-page HTML dashboard analysing the Indian gold market from 2019 to 2024 — covering investment funnels, jewellery purchase behaviour, price trends, and methodology.

## 🔗 Live Demo

> Upload `index.html` to [GitHub Pages](https://pages.github.com/) or open it directly in any browser — no server or dependencies required.

## 📊 Dashboard Pages

| Page | Description |
|------|-------------|
| **Executive Summary** | KPI overview, investment & jewellery funnels, price trend |
| **Investment Insights** | Channel distribution, investor demographics, detailed funnel |
| **Jewelry Market Insights** | Purchase funnel, stage distribution, price sensitivity |
| **Gold Price Trends** | Avg/Max prices, YoY growth, 3-year moving average |
| **Methodology & Overview** | Data sources, DAX measures, KPIs, conclusions |

## 📁 File Structure

```
├── index.html    # Complete self-contained dashboard (HTML + CSS + JS)
└── README.md     # Project documentation
```

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript
- **Charts:** [Chart.js v4.4.1](https://www.chartjs.org/) (via CDN)
- **Fonts:** Cormorant Garamond + DM Sans (via Google Fonts)
- **Data:** Embedded in-file (no backend or API required)

## 📈 Data Sources

- **MCX India** — Daily gold spot price (INR/10g)
- **World Gold Council (WGC)** — Demand and investor reports
- **IBJA** — India Bullion & Jewellers Association price bulletin
- **RBI** — Inflation (CPI) and monetary policy data
- **Industry Survey** — Customer funnel simulation (n = 12,400)

## 🚀 How to Use

### Option 1 — Open locally
```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git

# Open in browser
open index.html
```

### Option 2 — GitHub Pages
1. Go to **Settings → Pages** in your GitHub repository
2. Set source to **Deploy from a branch → main / root**
3. Visit `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## 📌 Key Metrics (2024)

| Metric | Value |
|--------|-------|
| Max Gold Price | ₹79,000 / 10g |
| 6-Year CAGR | 15.4% |
| Total Investors (funnel top) | 12,400 |
| Investment Conversion Rate | 23.8% |
| Jewellery Conversion Rate | 19.4% |
| Biggest Drop-off Stage | Awareness → Interest (–42%) |

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
