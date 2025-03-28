# ✈ Aviation Risk Analysis for Business Expansion  

##  Project Overview  
This project aims to help a company **expand into aviation** by identifying **low-risk aircraft models** for commercial and private use.  
Using historical **aviation accident data (1962-2023)**, we analyze **risk factors, survivability rates, and flight phase impacts** to make **data-driven recommendations** on aircraft selection.  

##  Business Problem Statement  
The company is venturing into the aviation industry but **lacks expertise in aircraft safety**.  
The goal is to determine:  
- ✅ Which **aircraft models** are the safest for commercial and private use?  
- ✅ What **flight phases** pose the greatest risk?  
- ✅ How do **weather and external factors** impact aviation safety?  
- ✅ What **strategies and methods** should the company adopt to mitigate future risks?  

##  Data Source & Methodology  
- **Dataset:** National Transportation Safety Board (NTSB) records (1962-2023)  
- **Key Metrics:**  
  - **Risk Score** – Severity of accidents
     calculated as: (Total.Fatal.Injuries×3)+(Total.Serious.Injuries×2)+(Total.Minor.Injuries×1) --Helps in ranking aircraft models based on overall risk.
  - **Survivability Rate** – Chance of survival in accidents  
  - **Fatality Rate** – Percentage of deaths per aircraft  
  - **Flight Phase Risk Score** – Risk impact at different flight stages
  - **Flight Purpose Risk** -
    calculated as:	∑(Risk.Score) /Total Accidents for that Purpose -- to determine best overall flight purpose
 

- **Tools Used:**  
  - **Python (Pandas, Matplotlib, Seaborn)** – Data cleaning & analysis  
  - **Tableau** – Data visualization  
  - **Jupyter Notebook** – Exploratory data analysis (EDA)  
  - **PowerPoint** – Presentation  


##  Presentation  
 **[Click here to view the PowerPoint presentation](./presentation/presentation.pdf)** 

## Tableau 
** https://public.tableau.com/views/flightdrawings/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link **
