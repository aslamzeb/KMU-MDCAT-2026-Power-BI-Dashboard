# KMU-MDCAT 2026 – Power BI Data Analysis Dashboard

An interactive educational data analytics project developed using Microsoft Power BI to explore student demographics, district-wise representation, academic backgrounds, and aggregate distribution.

## Dashboard Preview

<img width="1672" height="941" alt="KMU-MDCAT 2026 Student Analytics Dashboard" src="https://github.com/user-attachments/assets/6a5eeb8d-3556-4fb4-9d86-3cd1b8569bde" />

<img width="1351" height="766" alt="KMU MBBS Open Merit Analysis" src="https://github.com/user-attachments/assets/35e22700-07a9-4c7d-abd8-cb6d75fbff9f" />

<img width="1536" height="1024" alt="KMU-MDCAT 2026 Data Analytics Infographic" src="https://github.com/user-attachments/assets/98a8ca95-b557-4234-b7ac-84eaefc86160" />

---

## 1. Project Overview

This project presents an interactive Power BI dashboard developed to explore and analyze KMU-MDCAT 2026 student data.

The dashboard provides a multidimensional analysis of student demographics, gender distribution, district-wise representation, HSSC examination boards, HSSC completion years, and age-wise distribution.

A particular focus is placed on students achieving an **aggregate of 92% or above**, allowing the exploration of geographical, demographic, and educational patterns within this selected group.

The primary objective is to transform educational data into meaningful visual insights that support data exploration and evidence-based interpretation.

## 2. Dataset Overview

| Description | Value |
|---|---:|
| Total Records | 2,334 |
| Male Students | 1,045 (44.77%) |
| Female Students | 1,289 (55.23%) |
| Aggregate Threshold | ≥ 92% |
| HSSC Completion Years | 2018–2026 (represented years) |
| Examination | KMU-MDCAT 2026 |

## 3. Key Analytical Findings

### 3.1 Gender Distribution

Female students account for 55.23% of the dataset, compared with 44.77% male students.

- Female: 1,289 (55.23%)
- Male: 1,045 (44.77%)

Female representation exceeds male representation by approximately 10.46 percentage points.

**Insight:** Female students constitute the larger share of the available records.

### 3.2 District-Wise Distribution

The district-wise visualization identifies the leading districts among students achieving an aggregate of 92% or above.

| District | Students |
|---|---:|
| Swat | 268 |
| Mardan | 251 |
| Swabi | 164 |
| Lower Dir | 154 |
| Peshawar | 134 |
| Abbottabad | 131 |
| Nowshera | 126 |
| Karak | 121 |
| Mansehra | 116 |
| Charsadda | 111 |

**Key Insight:** Swat and Mardan have the highest reported counts in the district-wise aggregate analysis.

Other represented districts include D.I. Khan, Haripur, Buner, Malakand, Shangla, Kohat, Bannu, Upper Dir, Lower Dir, and others.

### 3.3 HSSC Board-Wise Analysis

The HSSC board-wise distribution highlights the educational backgrounds of students represented in the dataset.

| HSSC Board | Students |
|---|---:|
| BISE Peshawar | 538 |
| BISE Mardan | 383 |
| BISE Swat | 339 |
| BISE Abbottabad | 286 |
| FBISE | 283 |
| BISE Malakand | 175 |
| BISE D.I. Khan | 130 |
| BISE Kohat | 109 |
| BISE Bannu | 54 |

**Key Insight:** BISE Peshawar has the highest representation, followed by BISE Mardan and BISE Swat.

### 3.4 HSSC Completion-Year Analysis

One of the interesting findings of this project is the presence of students from earlier HSSC completion years who also achieved an aggregate of 92% or above.

| HSSC Completion Year | Students | Percentage |
|---|---:|---:|
| 2018 | 1 | 0.04% |
| 2019 | 1 | 0.04% |
| 2021 | 3 | 0.13% |
| 2022 | 11 | 0.47% |
| 2023 | 37 | 1.59% |
| 2024 | 204 | 8.74% |
| 2025 | 630 | 26.99% |
| 2026 | 1,447 | 62.00% |
| **Total** | **2,334** | **100%** |

**Key Observations:**

- 2026 contributes the largest share, with 1,447 students (62.00%).
- 2025 contributes 630 students (26.99%).
- Approximately 89% of the represented students completed HSSC in 2025 or 2026.
- Students from 2018 and 2019 also appear in the aggregate ≥92% group, with one student from each year.
- Three students from the 2021 HSSC cohort also achieved an aggregate of 92% or above.
- Students from 2022, 2023, and 2024 are also represented.

**Important Research Observation:**

The presence of students from earlier HSSC cohorts, particularly 2018, 2019, and 2021, raises interesting questions about the relationship between HSSC completion year, the time gap before MDCAT participation, and academic performance.

This observation provides an opportunity for further educational data analysis.

### 3.5 Age-Wise and Gender Analysis

The dashboard provides a comparative view of male and female students across different age groups.

It enables exploration of:

- Gender representation across age groups.
- Age distribution patterns.
- Differences between male and female student representation.
- Concentration of students within particular age brackets.

**Key Insight:** The dashboard indicates that student representation is concentrated mainly within the 17–20 age range.

---

## 4. Dashboard Features

The Power BI dashboard includes the following analytical components:

- Interactive district filters.
- HSSC board filters.
- HSSC completion-year filters.
- Gender filters.
- Age-group filters.
- Gender distribution donut chart.
- District-wise aggregate treemap.
- HSSC board-wise distribution chart.
- HSSC completion-year distribution.
- Age-wise gender comparison.
- Male and female KPI cards.
- HSSC year-wise gender distribution table.
- District-wise gender comparison matrix.
- Interactive cross-filtering and data exploration.

## 5. Tools and Technologies

| Technology | Application |
|---|---|
| Microsoft Power BI Desktop | Dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | Measures and calculations |
| Data Modeling | Structuring analytical relationships |
| Data Visualization | Interactive charts and reports |
| Exploratory Data Analysis | Identifying patterns and insights |

## 6. Analytical Value and Research Opportunities

This project demonstrates how Business Intelligence and Data Analytics can transform educational datasets into meaningful visual information.

Beyond descriptive reporting, the findings create opportunities for further investigation.

Potential research directions include:

1. Exploring the relationship between HSSC completion year and MDCAT aggregate.
2. Comparing demographic patterns across districts.
3. Investigating gender representation across different academic cohorts.
4. Examining the educational backgrounds of students achieving high aggregates.
5. Exploring the time gap between HSSC completion and MDCAT participation.

## 7. Important Data Interpretation Notes

- The district-wise figures represent counts of students with aggregates of 92% or above, not district-level success rates.
- The HSSC year-wise figures represent students within the selected dataset of 2,334 records.
- The presence of earlier HSSC cohorts does not establish that earlier candidates have higher or lower success rates.
- District and board representation should not be interpreted as comparative academic performance without appropriate denominator data.
- Findings are descriptive and do not establish causal relationships.

## 8. Project Purpose

Developed as an educational data analytics and visualization portfolio project to demonstrate practical applications of Business Intelligence, Applied Mathematics, and Data Science in educational data analysis.

The project reflects an interest in converting raw educational data into understandable, interactive, and research-oriented insights.

---

## Author

**Aslam Zeb**

**Make and Designed by: Aslam Zeb**

**Fields:** Data Science | Data Analytics | Applied Mathematics | Business Intelligence

**Tools:** Microsoft Power BI | DAX | Power Query | Data Modeling
