# Unemployment and Skill Gap Analysis in India

## 📌 Project Overview
This project presents a **state-level analysis of unemployment and skill gaps in India** by integrating labour market indicators with higher education enrolment data. Using official Government of India datasets, the study examines whether higher education outcomes are translating into improved employment opportunities across states and Union Territories.

The analysis focuses on identifying **education–employment mismatches**, regional disparities, and policy-relevant insights to support data-driven workforce planning.

---

## 🎯 Objectives
- Analyse state-level unemployment patterns in India  
- Examine labour force participation and employment absorption  
- Assess higher education enrolment as a proxy for graduate supply  
- Identify potential skill mismatches across states  
- Derive policy-oriented insights and recommendations  

---

## 📊 Data Sources
All datasets used in this project are sourced from official government platforms:

- **Periodic Labour Force Survey (PLFS)**  
  Ministry of Statistics and Programme Implementation (MoSPI)  
  Indicators used:
  - Unemployment Rate (UR)
  - Labour Force Participation Rate (LFPR)
  - Worker Population Ratio (WPR)

- **All India Survey on Higher Education (AISHE)**  
  Ministry of Education  
  Indicator used:
  - Estimated enrolment at various higher education levels (proxy for graduate supply)

Data was accessed via the **National Data and Analytics Platform (NDAP)**.

---

## 🛠️ Methodology
The analysis followed a structured workflow:

1. Data collection from PLFS and AISHE  
2. Data cleaning and preprocessing  
   - Standardisation of state names  
   - Handling of missing values  
   - Data type conversion  
3. Aggregation of PLFS indicators at the state level  
4. Aggregation of AISHE enrolment across education levels and gender  
5. Data validation and logical consistency checks  
6. Integration of labour market and education datasets  
7. Exploratory data analysis and visualisation  
8. Interpretation of skill gaps and policy implications  

---

## ✅ Validation Checks
To ensure analytical reliability, the following checks were performed:

- State and Union Territory coverage verification  
- Missing value assessment  
- Range validation of indicators  
- Logical consistency checks (e.g., **WPR ≤ LFPR**)  
- Duplicate state detection  

All validation checks passed successfully.

---

## 📈 Key Insights
- Significant variation exists in unemployment rates across states  
- Higher graduate supply does not consistently correspond to lower unemployment  
- Several states exhibit **high education output alongside high unemployment**, indicating potential skill mismatches  
- Gaps between labour force participation and employment highlight underutilised labour potential  

---

## 🧠 Policy Relevance
The findings suggest that:
- Expansion of higher education alone is insufficient to reduce unemployment  
- Skill development initiatives should be **region-specific and demand-driven**  
- Integrated use of PLFS and AISHE data can enhance workforce planning and policy design  

---

---

## 💻 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib)
- Google Colab
- GitHub
- draw.io (for workflow diagram)

---

## ⚠️ Limitations
- Analysis is conducted at the state level and does not capture intra-state variation  
- AISHE enrolment is used as a proxy for graduate supply and does not directly measure skill quality  
- Missing values due to non-reporting were conservatively handled  

---

## 📌 Author
Ashish Vasala 
B.Tech Student | Data Analysis Intern  
MLR institute of technology 

---

## 📜 License
This project is intended for academic, research, and learning purposes using publicly available government data.

