# Assessing the Impact of Public Transit Infrastructure on Housing Affordability  
**The Purple Line Corridor Case Study**  

**URSP601-0101: Research Methods**  
Insha Sheikh, Alexander Sklar, Homayoon Aghili  

---

## Introduction  
The Purple Line is a new Metro extension connecting Montgomery and Prince George's counties in the DC area. With 21 stations, it is designed to improve commuting, enhance connections to other transit services, and promote sustainability by encouraging public transit use.

---

## Research Question  
Has housing affordability (Mean Rent Value and Median Rent Value) in block groups within a half-mile radius of New Carrollton and Riverdale Purple Line Stations been negatively impacted by the Purple Line construction between 2018 and 2022 compared to 2013-2017 before the constructions began?

---

## Hypotheses  

### Alternative Hypothesis (H₁):  
Housing affordability (measured by Mean Rent Value and Median Rent Value) in block groups within a half-mile radius of the New Carrollton and Riverdale Purple Line corridors has significantly decreased (rent values have increased) during the construction period (2018-2022) compared to the pre-construction period (2013-2017).

### Null Hypothesis (H₀):  
There is no significant change in housing affordability (Mean Rent Value and Median Rent Value) in block groups within a half-mile radius of the New Carrollton and Riverdale Purple Line corridors during the construction period (2018-2022) compared to the pre-construction period (2013-2017).

---

## Tools Used  
- **Excel**  
- **ArcGIS Pro**  
- **R Studio**  

---

## Methodology  

### Data Sources  
1. **American Community Survey (ACS)** for two periods: 2013-2017 and 2018-2022  
2. **NHGIS**, for extracting the target geography in a census block group scale  
3. **SVI**, for including socioeconomic variables  

### Data Wrangling  
- **ArcGIS Pro:**  
  - Extracted data and prepared for analysis using the PLCC’s Purple Line Corridor sub-areas.  
  - Defined treatment group (block groups within half a mile of the nearest Purple Line Station) and control group (block groups between half a mile and one and a half miles from the nearest station).  

### Data Imputation and Hypothesis Testing  
- **R Studio:**  
  - Used Predictive Mean Matching (PMM) to impute missing data.  
  - Performed Difference-in-Differences (DiD) analysis to test the hypothesis.  

Results:  
The DiD test results failed to reject the null hypothesis. Further analysis with additional controlled variables showed some observed changes but limited statistical significance.  

---

## Research Visualizations  
1. **R:**  
   - Created spatial visualizations using Leaflet and ggplot2.  
2. **Tableau:**  
   - Developed a Tableau Story with interactive dashboards to showcase results.  

[**Link to the Tableau Story**]()  

[**Link to the R Markdown**]()  

---

## Conclusion  
While the Purple Line construction has affected factors like median family income, rent, and poverty levels, the results lack strong statistical significance. However, some variables, including the Number of Renter-Occupied Housing Units and the Percentage of Minorities in the treatment area, showed significant changes after the construction began.  

---
