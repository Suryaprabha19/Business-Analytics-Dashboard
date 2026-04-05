# 📊 Business Analytics Dashboard

An Excel-based investment behavior analytics dashboard built from a survey of **40 participants**, analyzing their investment preferences, saving objectives, expected returns, and information sources. The dashboard provides interactive filters and multiple chart types for exploring the data across gender, purpose, source, and savings goals.

---

## 🗂️ Workbook Structure

| Sheet | Purpose |
|-------|---------|
| `Data_set_2` | Raw CSV data loaded into Excel |
| `Dashboard` | Interactive visual dashboard |
| `Sheet1–Sheet8`, `Sheet12` | Supporting pivot/calculation sheets |

---

## 👥 Survey Overview

| Attribute | Details |
|-----------|---------|
| Total Participants | **40** |
| Age Range | 21 – 35 years |
| Gender | 25 Male (63%), 15 Female (37%) |
| Data Period | 2024 |

---

## 📊 Dashboard Sections

### 1. 🧑‍🤝‍🧑 Gender Distribution
| Gender | Count | Share |
|--------|-------|-------|
| Male | 25 | 63% |
| Female | 15 | 37% |

---

### 2. 💰 Distribution of Saving Objective
Tracks whether participants actively invest:
| Response | Count | Share |
|----------|-------|-------|
| Yes | 37 | 93% |
| No | 3 | 7% |

---

### 3. 📅 Distribution of Investment Duration
| Duration | Count |
|----------|-------|
| 3–5 years | 19 |
| 1–3 years | 18 |
| Less than 1 year | 2 |
| More than 5 years | 1 |

---

### 4. 📈 Analysis of Investment Expectations Among Participants
| Expected Return | Count |
|----------------|-------|
| 20%–30% | 32 |
| 30%–40% | 5 |
| 10%–20% | 3 |

---

### 5. 📡 Frequency of Information Source
| Source | Count |
|--------|-------|
| Financial Consultants | 16 |
| Newspapers and Magazines | 14 |
| Television | 6 |
| Internet | 4 |

---

## 🔍 Filter Panel (Slicers)

The dashboard includes **four interactive slicers**:

| Slicer | Options |
|--------|---------|
| **Gender** | Female, Male |
| **Purpose** | Returns, Savings for Future, Wealth Creation |
| **What are your savings objectives?** | Education, Health Care, Retirement Plan |
| **Source** | Financial Consultants, Internet, Newspapers & Magazines, Television |

All charts respond dynamically to slicer selections.

---

## 🗃️ Dataset — Column Reference

The CSV contains **40 rows** and **24 columns**:

| Column | Description |
|--------|-------------|
| `gender` | Male / Female |
| `age` | Age of participant (21–35) |
| `Investment_Avenues` | Actively invests? (Yes / No) |
| `Mutual_Funds` | Preference rank for Mutual Funds |
| `Equity_Market` | Preference rank for Equity Market |
| `Debentures` | Preference rank for Debentures |
| `Government_Bonds` | Preference rank for Government Bonds |
| `Fixed_Deposits` | Preference rank for Fixed Deposits |
| `PPF` | Preference rank for Public Provident Fund |
| `Gold` | Preference rank for Gold |
| `Stock_Marktet` | Stock market interest indicator |
| `Factor` | Primary investment factor (Returns / Risk / Locking Period) |
| `Objective` | Investment objective (Capital Appreciation / Growth / Income) |
| `Purpose` | Purpose (Wealth Creation / Savings for Future / Returns) |
| `Duration` | Investment duration preference |
| `Invest_Monitor` | How often investment is monitored |
| `Expect` | Expected returns range (10%–20%, 20%–30%, 30%–40%) |
| `Avenue` | Preferred investment avenue (Mutual Fund / Equity / FD / PPF) |
| `What are your savings objectives?` | Education / Health Care / Retirement Plan |
| `Reason_Equity` | Reason for choosing Equity |
| `Reason_Mutual` | Reason for choosing Mutual Funds |
| `Reason_Bonds` | Reason for choosing Bonds |
| `Reason_FD` | Reason for choosing Fixed Deposits |
| `Source` | Primary information source for investments |

---

## 📌 Preferred Investment Avenues

| Avenue | Count |
|--------|-------|
| Mutual Fund | 18 |
| Equity | 10 |
| Fixed Deposits | 9 |
| Public Provident Fund | 3 |

---

## 🔑 Key Insights

- **93%** of participants actively invest, showing high financial engagement in the survey group.
- **Wealth Creation** is the dominant investment purpose (32 out of 40 participants).
- Most participants prefer a **1–5 year** investment horizon — short to medium term.
- **20%–30% returns** is the most commonly expected outcome (80% of participants).
- **Financial Consultants** are the most trusted information source, ahead of digital media.
- **Retirement Plan** is the top savings objective, chosen by 60% of participants.
- **Mutual Funds** are the most preferred investment avenue, followed by Equity.

---

## 🛠️ Tools Used

- **Microsoft Excel** — Pivot Tables, Donut Charts, Bar Charts, Pie Charts, Slicers
- **CSV** — Raw data source (Business_Analytics_Dashboard.csv)

---

## 📄 License

This dataset is intended for academic and business analytics educational purposes.
