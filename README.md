<div align="center">

# 📊 Beyond Jobless — A Visual Analysis of U.S. Labor Dynamics

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](#)
[![Power Query](https://img.shields.io/badge/Power_Query-742774?style=for-the-badge&logo=microsoft&logoColor=white)](#)
[![DEPI](https://img.shields.io/badge/🏆_DEPI-Top_Project-gold?style=for-the-badge)](#-achievements)

**A comprehensive data-driven exploration of the U.S. labor market, analyzing unemployment trends, workforce participation, employment-to-population ratios, and state-level disparities — powered by 15M+ rows of real-world data.**

🎓 *Graduation Project — Digital Egypt Pioneers Initiative (DEPI)*

---

</div>

## 🎯 Project Overview

**Beyond Jobless** goes far beyond simple unemployment statistics. This project delivers a **multi-dimensional analysis** of the U.S. labor market, combining economic indicators, geographic data, and historical trends to provide actionable insights for job seekers, policymakers, and researchers.

### What Makes This Project Unique?

- 📈 **Long-term trend analysis** spanning from **1976 to 2025** (unemployment data)
- 🏦 **Economic crisis impact assessment** including the **2008 Financial Crisis** and **COVID-19 Pandemic**
- 🗺️ **State-by-state comparative analysis** across all 50 U.S. states
- 💼 **Jobs & Wages Atlas** — a comprehensive employment landscape by industry and location
- 🔍 **Market saturation analysis** — is your field in demand or oversaturated?
- 🚀 **Migration & employment correlation** — linking workforce movement with opportunity

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Data Sources & Scale](#-data-sources--scale)
- [Methodology](#-methodology)
- [Dashboard Highlights](#-dashboard-highlights)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Achievements](#-achievements)
- [Team](#-team)
- [Getting Started](#-getting-started)
- [License](#-license)

---

## ✨ Key Features

<table>
<tr>
<td width="50%">

### 📉 Unemployment Analysis
- Historical unemployment rates (1976–2025)
- Trend decomposition & pattern recognition
- Crisis period deep-dives (2008, 2020)
- Seasonality analysis

</td>
<td width="50%">

### 👥 Workforce Participation
- Labor force participation rates over time
- Employment-to-population ratio tracking
- Demographic breakdowns
- State-level workforce comparisons

</td>
</tr>
<tr>
<td width="50%">

### 💰 U.S. Jobs & Wages Atlas
- Occupation-level wage analysis (2007–2024)
- State-by-state salary comparisons
- Industry growth & decline tracking
- Best-paying states per occupation

</td>
<td width="50%">

### 🗺️ Job Availability & Market Insights
- Field demand vs. saturation analysis
- Best states for each specialization
- Employment–unemployment–wages correlation
- Interstate migration impact on labor markets

</td>
</tr>
</table>

---

## 📊 Data Sources & Scale

| Source | Description | Coverage | Volume |
|--------|------------|----------|--------|
| **Bureau of Labor Statistics (BLS)** | State-level occupational employment & wage data | 2007–2024 | 15M+ rows |
| **U.S. Census Bureau** | Population & demographic data | Multiple years | — |
| **Immigration Statistics** | State-level immigration data | 2025 | 50 states |
| **Labor Force Statistics** | Unemployment & participation rates | 1976–2025 | Time series |

> **Total Dataset Size:** 15,000,000+ rows of real-world economic data

---

## 🔧 Methodology

```mermaid
graph LR
    A["1. Data Collection"] --> B["2. Data Cleaning"]
    B --> C["3. Data Modeling"]
    C --> D["4. Analysis & Visualization"]
    D --> E["5. AI-Powered Insights"]
    
    style A fill:#4CAF50,stroke:#333,color:#fff
    style B fill:#2196F3,stroke:#333,color:#fff
    style C fill:#FF9800,stroke:#333,color:#fff
    style D fill:#9C27B0,stroke:#333,color:#fff
    style E fill:#F44336,stroke:#333,color:#fff
```

### 1️⃣ Data Collection
- Gathered real-world labor market data from official U.S. government sources
- Compiled long-running time series spanning nearly **50 years**
- Integrated cross-sectional data across all **50 states**

### 2️⃣ Data Cleaning & Transformation
- **Power Query** + **M Language** for advanced data preprocessing
- Handled missing values, standardized formats, and corrected data types
- Applied normalization techniques for cross-dataset compatibility

### 3️⃣ Data Modeling
- Built a **star schema** data model linking state-level tables
- Integrated economic indicators with geographic dimensions
- Created calculated columns and measures using **DAX**

### 4️⃣ Analysis & Visualization
- Designed **interactive Power BI dashboards** with drill-through capabilities
- Implemented **time-intelligence functions** for year-over-year comparisons
- Built dynamic filters for state, year, and occupation-level exploration

### 5️⃣ AI-Powered Insights
- Leveraged **AI tools** for anomaly detection and trend forecasting
- Applied statistical methods to identify significant labor market shifts

---

## 📸 Dashboard Highlights

> 🔗 **Full dashboard export available in** [`Beyond Jobless.pdf`](./Beyond%20Jobless.pdf)

### Key Dashboards Include:

| Dashboard | Description |
|-----------|-------------|
| **Unemployment Overview** | National trends with crisis annotations (1976–2025) |
| **State Comparison** | Interactive map with state-by-state KPIs |
| **Economic Indicators** | Multi-metric analysis (2008–2024) |
| **Jobs & Wages Atlas** | Occupation-level employment & salary explorer |
| **Market Insights** | Demand vs. saturation analysis by field |
| **Migration Impact** | Interstate workforce movement & employment correlation |

---

## 🛠️ Tech Stack

<div align="center">

| Tool | Purpose |
|------|---------|
| ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) | Interactive dashboards & visualizations |
| ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white) | Data storage & initial exploration |
| ![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat-square&logo=microsoft&logoColor=white) | Calculated measures & KPIs |
| ![Power Query](https://img.shields.io/badge/Power_Query-742774?style=flat-square&logo=microsoft&logoColor=white) | ETL & data transformation (M Language) |
| ![AI Tools](https://img.shields.io/badge/AI_Tools-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) | Trend analysis & insight generation |

</div>

---

## 📁 Project Structure

```
Beyond-Jobless-Project/
│
├── 📊 Beyond Jobless.pbix          # Power BI Dashboard (main file)
├── 📄 Beyond Jobless.pdf           # Dashboard export (PDF)
├── 📑 Beyond Jobless.pptx          # Project presentation
├── 🎬 Demo.mp4                     # Live demo recording
│
├── 📂 Data/
│   ├── state_May2007_dl.xlsx       # BLS Occupational Data 2007
│   ├── state_M2008_dl.xlsx         # BLS Occupational Data 2008
│   ├── state_M2009_dl.xlsx         # ...
│   ├── state_M2010_dl.xlsx
│   ├── state_M2011_dl.xlsx
│   ├── state_M2012_dl.xlsx
│   ├── state_M2013_dl.xlsx
│   ├── state_M2014_dl.xlsx
│   ├── state_M2015_dl.xlsx
│   ├── state_M2016_dl.xlsx
│   ├── state_M2017_dl.xlsx
│   ├── state_M2018_dl.xlsx
│   ├── state_M2019_dl.xlsx         # BLS Occupational Data 2019
│   ├── state_M2020_dl.xlsx         # ...
│   ├── state_M2021_dl.xlsx
│   ├── state_M2022_dl.xlsx
│   ├── state_M2023_dl.xlsx
│   ├── state_M2024_dl.xlsx         # BLS Occupational Data 2024
│   ├── ststdsadata.xlsx            # State-level statistics
│   ├── Major For Jops.xlsx         # Major occupation categories
│   └── immigrants-by-state-2025.xlsx # Immigration data by state
│
└── 📄 README.md                    # This file
```

---

## 🏆 Achievements

<div align="center">

### 🥇 Nominated as a **Top Project** in the  
### **Digital Egypt Pioneers Initiative (DEPI)**

</div>

After being nominated among the **Top Projects** in DEPI, the team expanded the project scope significantly:

- ✅ Started with **unemployment analysis** as the core
- ✅ Expanded to include a full **U.S. Jobs & Wages Atlas**
- ✅ Added **Job Availability & Market Insights** module
- ✅ Built **field demand vs. saturation** analysis
- ✅ Identified **best states per specialization**
- ✅ Correlated **employment, unemployment, wages & migration** across states
- ✅ Delivered a **live demo** exceeding project requirements

> *"The goal was not just numbers — but a decision-making tool:*  
> *Where should I work? Should I relocate? What's the future of my field?"*

---

## 👥 Team

<div align="center">

| Team Member |
|-------------|
| **Mustafa Adel** |
| **Basmala Helmy** |
| **Habiba Amr** |
| **Mariam Elsherbiny** |

</div>

---

## 🚀 Getting Started

### Prerequisites
- **Microsoft Power BI Desktop** (latest version recommended)
- At least **8 GB RAM** for optimal dashboard performance

### How to Use
1. **Clone this repository:**
   ```bash
   git clone https://github.com/KHALEDRABBAH/US-Unemployment-Dashboard.git
   ```
2. **Open the dashboard:**
   - Launch `Beyond Jobless.pbix` in Power BI Desktop
3. **Explore the data:**
   - Use the interactive filters to drill down by state, year, and occupation
   - Navigate between dashboard pages using the tabs at the bottom

### Data Files
All raw data files are included in this repository for full reproducibility. The datasets are sourced from official U.S. government agencies and are publicly available.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### ⭐ If you found this project insightful, please give it a star!

**Made with ❤️ by the Beyond Jobless Team**

*Digital Egypt Pioneers Initiative (DEPI) — Graduation Project*

---

[![GitHub](https://img.shields.io/badge/GitHub-KHALEDRABBAH-181717?style=for-the-badge&logo=github)](https://github.com/KHALEDRABBAH)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/khaledrabbah/)

</div>
