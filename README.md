# Global disparities in the introduction, scale-up, and evaluation of the effectiveness of COVID-19 vaccines

We linked large public datasets to systematically quantify global disparities in COVID-19 vaccine introduction, scale-up, and vaccine effectiveness (VE). This GitHub page contains the data processing, statistical analysis, and visualisations R code.

## Input Data
  
  - **Vaccine introduction dates:**
    - WHO COVID-19 database as of 07 January 2024 (Input/Vaccine_data/vaccination-data.csv),
    - Our World in Data (OWID) COVID-19 vaccination database as of 07 January 2024 (Input/Vaccine_data/owid-covid-data.csv), and
    - OWID COVID-19 vaccine platforms database as of 07 January 2024 (Input/Vaccine_data/owid_vaccine_plat.csv) 
 
  - **Primary series vaccine coverage data:**
    - OWID COVID-19 vaccination database as of 07 January 2024 (Input/Vaccine_data/vaccination-data.csv)  
  
  - **Primary series coverage estimates high-risk populations (healthcare workers and older adults)**
    - WHO/UNICEF COVID-19 Vaccination Information Hub (Input/Vaccine_data/WHO_UNICEF_data/who_unicef_country_timeseries_data.csv)
  
  - **COVID-19 VE studies:**
    - VIEW-hub living literature review (Input/WeeklySummary_COVID19_VE_Studies_20230622.xlsx) as of 11 January 2024
  
  - **Country-level income status (2019):**
    - World Bank estimates of Gross National Income (GNI) per capita based on purchasing power parity method (Input/inequalities databases/GNI per capita (ppp)/GNI_per_c.csv) 

## Scripts
   
  - **Income inequalities database creation**
    - "1 Creation of GNI database.Rmd"
   
  - **Global differences in vaccine introduction and scale-up**
    - "2 Introduction and scale-up description (Fig 1).Rmd"
  
  - **COVID-19 Vaccine effectiveness database creation**
    - "3 Creation of VE database.Rmd"
   
  - **Global differences in the evaluation of vaccine effectiveness**
    - "4 VE description (Fig 2).Rmd"
   
  - **Vaccine effectiveness by income status**
    - "5 Meta-regression inclusion criteria.Rmd",
    - "6 Meta-regression variables.Rmd",
    - "7A Meta-regression results - BNT162b2.Rmd",
    - "7B Meta-regression results - mRNA-1273.Rmd",
    - "7C Meta-regression results - ChAdOx1-S.Rmd",
    - "7D Meta-regression results - Ad26.COV2.S.Rmd", and
    - "8 Meta-regression summary.Rmd"
