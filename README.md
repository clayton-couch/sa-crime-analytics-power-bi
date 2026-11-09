<h1 align="center">🇿🇦 South African Crime Analytics</h1>
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

- **Lockdown effect.** Total crime fell by about **[X]%** in 2020/21 and then recovered.
- **[Your Q2 finding about murder, rape or vehicle theft, with a number]**

---

## 🛠️ What I did

- 🧹 **Cleaned the data:** [list your cleaning steps]
- 🧮 **Wrote DAX measures:** Top 10 Stations (`TOPN` + `SUMX`), Top 10 % Share (`DIVIDE`), and year-based measures using `CALCULATE`
- 🎨 **Built the report:** KPI cards, combo chart, bubble map, Top 5 districts table, bar chart and gauge
- 🧠 **What I learned:** [one or two sentences in your own words]

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
SAPS crime statistics 2005–2026: [paste the link where you got the data]

## 👤 Author
**Clayton Couch** 
