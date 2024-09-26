
## Project Overview

The goal of this GITHUB repository is to data cleaning, imputation, analysis, and visualization to generate insights for our DSC-PHASE-1-PROJECT.

Main .ipynb notebook called **"student.ipynb"**
Powerpoint presentation called **presentation.pdf**

Two Tableua dashboard were created. The links to the dashboards are as follows:

https://public.tableau.com/app/profile/victor.kigen3018/viz/dsc-phase-1-project-dashboard/AirplaneMakeDashboard?publish=yes
https://public.tableau.com/app/profile/victor.kigen3018/viz/dsc-phase-1-project-dashboard/AviationDataDashboard



### Business Problem/Understanding

The business problem that was stated is as follows: 

**Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.**

### Data Cleaning/Analysis

The following steps were taken to ensure that the data was cleaned: 
*Columns that had no relevance to the business problem were dropped.Empty rows were also dropped.
*Using appropriate data analysis methods, certain categorical columns with empty entries were replaced with “most likely” results. Empty numerical columns were replaced with average figures.
*Pilot error related accidents were categorised to differentiate between Aircraft and Pilot accidents
*Case sensitivity was removed for categorical columns

In order to measure risk analysis, certain metrics were created:

*Fatality Rate
*Accident Frequency
*Pilot Error Rate
*Risk score - A combination of the accident frequency, fatality rate and pilot error was used in order for us to compare the different Aircraft Makes/Models.

Data used:
*(data/Aviation_Data.csv)
Clean data:
*airplane_data_clean.csv
*airplane_make_data.csv


## Conclusion

**Recommendation 1:** Only purchase aircrafts that have a low risk score 
**Recommendation 2:** Gather more financial and aircraft usage information in order to make a more informed decision
**Recommendation 3:** Purchase aircrafts that require less pilot training as this can directly have a negative financial impact. Pilot training is related to the number of pilot error related accidents.  

