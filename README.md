# ❄️ EU Pharma Cold Chain Monitor

A mock analytics project to track and evaluate cold chain temperature compliance across pharmaceutical shipments within EU member states, using Excel dashboards, simulated data, and GDP regulatory logic.

---

## 🎯 Objective

To simulate real-world cold chain risks and generate actionable insights for pharmaceutical logistics teams working under EU GDP (Good Distribution Practice) temperature standards, with the goal of improving product safety, reducing waste, and demonstrating Excel analytics proficiency.

---

## 📦 Simulated Dataset

- 100 pharmaceutical shipments
- Variables: product type, origin/destination countries, shipment dates, temperature readings, GDP annexes, status flags
- Focus on temperature-sensitive products (Insulin, mRNA Vaccines, Monoclonal Antibodies)

| Column               | Description                          |
|----------------------|--------------------------------------|
| Shipment_ID          | Unique ID per shipment               |
| Product              | Pharma type: Insulin, Vaccine, etc.  |
| Origin/Destination   | EU countries                         |
| Min_Temp / Max_Temp  | Simulated temperature readings       |
| GDP_Chapter          | Annex 9, 13, or 15                   |
| Status               | CRITICAL or OK                       |
| EU_Violation         | Flags GDP compliance breach          |

---

## 📊 Dashboard Overview

Created entirely in Excel using:
- PivotTables & PivotCharts
- Conditional formatting for risk heatmaps
- Time series visualisations
- Data validation & formulas

### Visuals Included
- **Route Risk Heatmap** (Avg Max Temp by Route)
- **Product Compliance Bar Chart** (CRITICAL vs OK)
- **Monthly Violation Trend Line Chart**
- GDP Reference Table for Annexes 9, 13, 15

---

## 🔑 Key Business Insights

### 🌍 High-Risk Shipping Routes (GDP Violation Risk)
| Route                  | Avg Max Temp |
|------------------------|--------------|
| **Italy → Germany**     | 14.7°C        |
| **Italy → Poland** | 13.5°C        |
| **Sweden → Greece**     | 13.2°C        |

➡️ *These are extremely higher than the 8°C GDP threshold. Recommend active cooling solutions or revised shipping routes.*

---

### 💉 Product Vulnerabilities
| Product              | CRITICAL Shipments (%) |
|----------------------|-------------------------|
| **Insulin**           | 78%                    |
| **Monoclonal Antibody** | 77%                    |
| **mRNA Vaccine**      | 64%                    |

➡️ *Cold-chain sensitive drugs require improved insulation or specialised packaging.*

---

### 📅 Seasonal Violation Trend
| Month | Violations |
|-------|------------|
| May   | 16         |
| Jun   | 10         |
| Jul   | 12         |
| Aug   | 5          |

➡️ *GDP violations spike between May and July. Recommend summer mitigation strategies across Southern EU.*

---

### 💰 Estimated Impact
> Based on simulated data, we estimated that approx. 29% of temperature excursions could lead to waste, and implementing targeted cooling strategies could reduce this by 20–30%. When scaled to an annual EU-level operation, that could translate to approx. €480K in savings.

---

## 🛠 Tools Used
- Microsoft Excel (PivotTables, conditional formatting, formulas)
- Simulated data modeling
- Business logic from EU GDP guidelines (Annex 9/13/15)

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `EU_Cold_Chain_Dashboard.xlsx` | Full working Excel dashboard |
| `dashboard_screenshot.png`     | Preview of visuals |
| `sample_data.csv`              | 10-row sample dataset |
| `README.md`                    | This document |

---

## 📌 Author

**Gayatri Ramakrishnan**  
MBA in Life Science Management | Regulatory Strategy | Healthcare Analytics  
📍 Berlin, Germany  
🔗 [LinkedIn](https://linkedin.com/in/gayatriramakrishnan30) | 🌐 Portfolio: https://github.com/gayatriramakrishnan30

---
