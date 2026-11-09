<h1 align="center">🔍 South African Crime Analytics</h1>
<p align="center"><b>A Power BI dashboard exploring SAPS crime statistics, 2005–2026</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge" alt="DAX">
  <img src="https://img.shields.io/badge/Data%20Cleaning-2E7D32?style=for-the-badge" alt="Data Cleaning">
</p>

---

## 📊 At a glance (2025/26)

| Total crimes | Top 10 stations' share | Top 5 districts |
|:---:|:---:|:---:|
| **1,89M** | **5,65%** | **821 278** (about 43%) |

---

## 🖥️ Dashboard in action

The screenshots below show my dashboard with **different districts clicked**. Each click filters the other visuals, so the map, charts and figures update to show that area's relevant crimes. *(Click any image to enlarge it.)*

<table>
<tr>
<td align="center"><img src="Screenshot%20(623).png" alt="Dashboard view 1" width="450"><br><sub>View 1</sub></td>
<td align="center"><img src="Screenshot%20(624).png" alt="Dashboard view 2" width="450"><br><sub>View 2</sub></td>
</tr>
<tr>
<td align="center"><img src="Screenshot%20(625).png" alt="Dashboard view 3" width="450"><br><sub>View 3</sub></td>
<td align="center"><img src="Screenshot%20(626).png" alt="Dashboard view 4" width="450"><br><sub>View 4</sub></td>
</tr>
<tr>
<td align="center"><img src="Screenshot%20(627).png" alt="Dashboard view 5" width="450"><br><sub>View 5</sub></td>
<td align="center"><img src="Screenshot%20(628).png" alt="Dashboard view 6" width="450"><br><sub>View 6</sub></td>
</tr>
</table>

---

## ❓ Questions I set out to answer

1. 📍 **Hotspots:** Which police stations record the most crime, and how much of the national total do the top 10 account for?
2. 📈 **Drivers:** How have murder, rape and vehicle theft changed over the past 10 years, and what happened in the 2020/21 lockdown year?
3. 🗺️ **Geography:** How do districts compare, and where is crime concentrated?

---

## 💡 Key findings

- **Crime is spread widely.** The top 10 stations make up only **5,65%** of national crime. Cape Town Central (16.8K) and Mitchells Plain (14.0K) lead.
- **A few big metros dominate.** The top 5 districts account for about **43%** of national crime.

| Rank | District | Crimes 2025/26 |
|:---:|---|---:|
| 1 | City of Cape Town | 254 209 |
| 2 | City of Johannesburg | 187 469 |
| 3 | eThekwini | 132 093 |
| 4 | City of Tshwane | 126 667 |
| 5 | Ekurhuleni | 120 840 |

- **Lockdown effect.** Total crime dipped in 2020/21, the COVID lockdown year, and recovered in the years that followed.
- **Trends over time.** Murder, rape and vehicle theft are tracked year by year over the past 10 years alongside total crime, so each trend and the lockdown dip can be compared in one chart.

---

## 🛠️ What I did

- 🧹 **Cleaned the data in Power Query:** changed data types, removed or corrected errors, and standardised the text (trimmed extra spaces and fixed capitalisation).
- 🧮 **Wrote DAX measures:** Top 10 Stations (`TOPN` + `SUMX`), Top 10 % Share (`DIVIDE`), and year-based measures using `CALCULATE`.
- 🎨 **Built the report:** KPI cards, combo chart, bubble map, Top 5 districts table, bar chart and gauge.

---

## 🧠 What I learned

- **Start with questions, not charts.** I wrote down the questions first, then chose one visual to answer each. Anything that didn't answer a question was left out.
- **DAX turns data into answers.** Writing measures like Top 10 Stations taught me how `TOPN`, `SUMX` and `DIVIDE` work together, and why a measure with a hard-coded year behaves differently from one that responds to filters.
- **Clicking one visual filters the others.** I learned how cross-filtering works and used Edit interactions to control which visuals react.
- **Check your numbers.** I verified the gauge by adding up the bars myself, and fixed chart details that could mislead, like unsorted years and a value axis that exaggerated the lockdown dip.

---

## 📂 Files

| File | What it is |
|---|---|
| `South African Crime Analytics Dashboard.pbix` | The Power BI report |
| `sapacr-2005-2026-v1.5.csv` | The dataset |
| `Screenshot (623).png` to `Screenshot (628).png` | Dashboard views with different districts clicked |

**To open it:** download the `.pbix` file and open it in the free [Power BI Desktop](https://powerbi.microsoft.com/desktop/).

---

## 📌 Data source
South African Police Service (SAPS) crime statistics, 2005–2026 (file: `sapacr-2005-2026-v1.5.csv`).

## 👤 Author
**Clayton Couch**
