
# 🇪🇺 Impact of Cultural and Sports Investments on Socio-Economic Development in Europe (2015–2021)

**Author**: Joel Mintchi  
**Technologies**: Python, Jupyter Notebook, Power BI, DAX  
**Scope**: 19 European countries | 7 years | 20 socio-economic indicators

---

## 🧩 Project Overview

This project analyzes how public investments in culture and sports influence youth well-being across Europe. It follows a structured three-phase approach:

1. **Data Collection & Preparation**  
2. **Exploratory Analysis & Indicator Design**  
3. **Interactive Visualization & Decision Insights**

It combines international datasets, advanced data processing, and visual storytelling to support evidence-based policymaking.

---

## 📁 Repository Structure

```
CultureSportImpactEU/
├── data/                      # Raw and cleaned datasets
│   ├── raw/                  # Original sources
│   └── processed/            # Final consolidated dataset
├── notebooks/                # Python scripts
│   ├── 01_data_collection.ipynb
│   └── 02_exploratory_analysis.ipynb
├── dashboard/                # Power BI file (.pbix)
├── docs/                     # Report, annexes, documentation
│   └── synthesis_report.pdf
├── README.md
├── LICENSE
└── .gitignore
```

---

## 🧪 Task 1: Data Collection & Preparation

### 🎯 Objective
Build a consolidated dataset from diverse sources, ready for analysis.

### 🔍 Methodology
- Identify reliable sources: international databases, open data portals, public reports
- Collect data via download, scraping, and APIs
- Harmonize formats: units, time periods, geographic granularity
- Merge datasets into a single structured file

### 📚 Sample Data Sources
- **Demographic**: [WorldPop](https://hub.worldpop.org), [UN Population](https://population.un.org/wpp)
- **Economic**: [IMF](https://data.imf.org), [OECD](https://www.oecd.org/en/data.html)
- **Social**: [WHO](https://www.who.int/data/gho), [UNDP](https://hdr.undp.org/data-center)
- **Culture/Sport**: Eurostat COFOG, FIFA Rankings

---

## 📊 Task 2: Exploration & Analysis

### 🎯 Objective
Transform the dataset into a rich analytical foundation.

### 🔍 Methodology
- Descriptive analysis: historical trends and spatial dynamics
- Derived indicators:
  - Annual growth rates
  - Youth population ratios
  - Composite indices: Wellbeing Index, Sport Culture Index
- Anomaly detection: countries with high investment but low impact
- Aggregations by region and normalization per capita

### 📁 Deliverables
- Enriched dataset (`processed/enriched_dataset.csv`)
- Analysis notebook (`notebooks/02_exploratory_analysis.ipynb`)
- Methodology documentation (`docs/anomalies_methodology.md`)

---

## 📈 Task 3: Visualization & Insights with Power BI

### 🎯 Objective
Design an interactive dashboard that supports strategic decision-making.

### 🧠 Dashboard Structure
- **Page 1**: Overview (KPI cards, choropleth map, top/bottom countries)
- **Page 2**: Temporal evolution (stacked areas, growth maps)
- **Page 3**: Comparative analysis (animated scatter, radar chart, normalized bars)
- **Page 4**: Insights & Actions (anomaly table, waterfall chart, correlation matrix)

### 🧪 Interactive Features
- Dynamic filters: year, region, sector
- Visual segments: country typologies (leaders, efficient, critical)
- Storytelling: each chart answers a strategic question

### 📁 Deliverables
- Power BI file: `dashboard/CultureSportImpactEU.pbix`
- Synthesis report: `docs/synthesis_report.pdf`

---

## 📬 Contact

**Joel Mintchi**  
📧 Mintchijo@email.com  
📍 Cotonou, Benin

