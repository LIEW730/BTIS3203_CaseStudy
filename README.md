# BTIS3203_CaseStudy

# BTPR3203 – Case Study: Sustainable Manufacturing & Industrial Automation in Malaysia

**Course:** BTPR3203 Python for Data Science  
**Semester:** 2026B  


---

## Research Questions

1. **Data Preparation**  
   What is the structure, completeness, and key descriptive statistics of the combined Industrial Production Index (IPI) and monthly electricity consumption datasets (2018–2024), and what cleaning steps are required?

2. **Analysis**  
   What is the strength and statistical significance of the relationship between overall manufacturing IPI and commercial/industrial electricity consumption, and which manufacturing divisions show the highest production growth?

3. **Visualisation**  
   How have manufacturing production and commercial/industrial electricity consumption evolved together from 2018 to 2024, and what patterns (including the COVID-19 period) are visible?

---

## Datasets Used

| Dataset | Source | Dimensions Covered | Period |
|---------|--------|--------------------|--------|
| Industrial Production Index by Division (2-digit MSIC) | Department of Statistics Malaysia (DOSM) | Temporal + Sectoral (Manufacturing) | Jan 2015 – May 2026 |
| Monthly Electricity Consumption by Sector | Energy Commission / DOSM | Temporal + Environmental (Energy Use) | Jan 2018 – Jun 2024 |

**Combined analysis period:** January 2018 – June 2024

- IPI data: [OpenDOSM / data.gov.my](https://storage.dosm.gov.my/ipi/ipi_2d.parquet)
- Electricity data: [data.gov.my](https://storage.data.gov.my/energy/electricity_consumption.csv)

---
## create and activate a virtual environmemnt
python -m venv venv

# Windows
venv\Scripts\activate

# macOS / Linux
source venv/bin/activate

---

##Key Findings (Summary)

- There is a strong and statistically significant positive correlation between overall manufacturing production (IPI) and commercial/industrial electricity consumption.
- Technology-intensive divisions, particularly Computer, electronic & optical products (MSIC 26) and Electrical equipment (MSIC 27), consistently rank among the highest in average production index and growth.
- Both manufacturing output and electricity consumption show a clear dip during the early COVID-19 period (2020), followed by recovery.
--Rising manufacturing output continues to be closely linked to higher electricity demand, highlighting the importance of energy efficiency for sustainable industrial growth.
