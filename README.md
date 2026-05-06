# 🏦 World Bank 2015 — Financial & Economic Analysis

**Author:** Anurag Das | **Dataset:** 2015 World Bank Data (264 countries, 11 indicators)  
**Focus:** Banking readiness, lending potential, trade finance, and digital financial services across world regions

---

## 📁 Project Structure

```
world-bank-analysis/
│
├── data/
│   └── 2015 World Bank data by nation and region.xls
│
├── images/
│   ├── missing_data.png
│   ├── gdp_by_region.png
│   ├── gdp_vs_internet.png
│   ├── exports_by_region.png
│   ├── lending_potential.png
│   ├── population_vs_internet.png
│   ├── country_benchmark.png
│   └── correlation_heatmap.png
│
├── notebooks/
│   └── world_bank_analysis.ipynb
│
└── README.md
```

---

## 📌 Project Overview

This project reframes the 2015 World Bank dataset through a **financial lens** — analyzing which regions and countries are best positioned for banking expansion, digital lending, stock market development, and trade finance.

**Dataset contains:**
- 264 countries
- 11 development indicators
- Data grouped by country and world region

---

## ❓ Key Financial Questions Answered

1. 🏦 Which regions have the strongest GDP base for **stock market and banking development**?
2. 💻 Does **internet penetration** predict digital banking readiness and fintech adoption?
3. 📦 Which regions are most **export-driven** — trade finance opportunities?
4. 💳 Which countries show the best profile for **lending and credit growth**?
5. 👥 How does **population size** relate to retail banking market potential?
6. 🇮🇳 Where does **India** stand as an emerging financial market?
7. 🔗 Which indicators are most **correlated with financial development**?

---

## 📊 Visualizations

### GDP by Region — Financial Market Depth
![GDP by Region](images/gdp_by_region.png)

### Internet Access vs GDP per Capita — Digital Banking Readiness
![GDP vs Internet](images/gdp_vs_internet.png)

### Exports as % of GDP — Trade Finance Potential
![Exports by Region](images/exports_by_region.png)

### Top 15 Countries by Lending Potential Score
![Lending Potential](images/lending_potential.png)

### Population vs Internet Access — Retail Banking Market Size
![Population vs Internet](images/population_vs_internet.png)

### Country Benchmark vs World Average
![Country Benchmark](images/country_benchmark.png)

### Correlation Heatmap — Financial Development Indicators
![Correlation](images/correlation_heatmap.png)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations & scoring |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Jupyter Notebook | Interactive analysis environment |
| Excel (.xls) | Raw data storage |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/dasanurag97-maker/world-bank-analysis.git
cd world-bank-analysis
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn openpyxl xlrd==1.2.0 jupyter
```

### 3. Run the notebook

- Open the project folder in **VS Code**
- Navigate to `notebooks/world_bank_analysis.ipynb`
- Click **"Run All"** to execute all cells

---

## 🔑 Key Financial Findings

1. **GDP & Capital Markets:** Europe and East Asia dominate global GDP — these regions have the deepest stock markets and most developed banking sectors.
2. **Digital Banking Readiness:** Internet penetration is strongly correlated with GDP per capita (r ≈ 0.75), making it a reliable proxy for fintech and digital lending adoption.
3. **Trade Finance:** Southeast Asia and Australasia are the most export-driven regions, generating strong demand for trade finance, letters of credit, and FX hedging.
4. **Lending Markets:** Large, literate, and increasingly wealthy populations (e.g., India, China, Brazil) score highest on lending potential — ideal markets for credit expansion.
5. **Retail Banking:** Countries combining high population with rising internet access represent the largest untapped retail banking markets for the next decade.
6. **India 🇮🇳:** Among the top 10 economies by total GDP, large population base, and rapidly growing internet penetration — a high-potential emerging market for banking, lending, and fintech.

---

## 💡 Financial Recommendations

1. **Target digital-first markets** — Countries with >50% internet penetration and growing middle class are ideal for neobank and digital lending expansion.
2. **Trade finance in Asia** — Southeast Asian export intensity makes it the top region for trade credit and supply chain finance products.
3. **Lending in emerging markets** — India, Nigeria, and Indonesia combine large populations with improving literacy, signaling strong future credit demand.

---

## 🔧 How to Extend This Project

| What to add | How |
|---|---|
| Real stock market data | Use `yfinance` or World Bank API for market cap data |
| Banking penetration | Add 'Account ownership (%)' from World Bank FINDEX |
| Credit-to-GDP ratio | Merge with IMF Financial Stability data |
| Time series analysis | Load multiple years (2010–2023) and plot trends |
| Machine learning | Predict lending risk scores using regression |

---

## 👤 Author

**Anurag Das** — [GitHub Profile](https://github.com/dasanurag97-maker)

---

## 📄 License

Copyright © 2026 dasanurag97-maker. All rights reserved.  
This project is for **viewing purposes only**. Unauthorized use is strictly prohibited.
