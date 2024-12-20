# lightch_capstone1

## UNITED STATES MILITARY ENLISTED ACCESSIONS
This project was a graduation requirement for Nashville Software School Data Analyst Bootcamp (DDA-14)

### Executive Summary
Military enlistment has declined in the Department of Defense (DoD) in recent decades. Enlistment in the US Armed Forces in 2020 decreased by approximately 58% since 1980 (https://usafacts.org/articles/is-military-enlistment-down/).  The decrease in enlistment from 2010 to 2020 was approximately 6%. Not all areas in the US have declining enlistment.  The SOUTH consistently exceeds recruitment compared to its target population.  This project examined one factor, Gross Domestic Product Per Capita (GDPPC), against Percent Enlisted Accessions from FY2010-2020, finding interesting results.  

### Motivation
“Only 1 percent of our population today will ever wear the uniform of this nation in any of its incarnations -- soldier, sailor, airman, Marine, active, Guard or Reserve,” [Vice Chairman Salutes The 1 Percent of Population That Serves > U.S. Department of Defense > Defense Department News](https://www.defense.gov/News/News-Stories/Article/Article/1563848/vice-chairman-salutes-the-1-percent-of-population-that-serves/)
I wanted to explore the statement that one percent of the US population will serve in uniform, focusing on enlisted recruitment in the DoD.

### Data Questions
This project explored three broad questions for US Department of Defense Enlisted Accessions 
* PQ1: What are the Enlisted Accession trends over time? 
* PQ2: Are there areas where Enlisted Accessions differs from the US population?
* PQ3: Is there a relationship between GDP Per Capita and Enlisted Accessions? 

### Technologies
I used Python libraries pandas, NumPy, seaborn, matplotlib, plotly, and RegEx, and MS PowerPoint and Excel

### Data Sources 
* United States Census Bureau US Census Index of /programs-surveys/popest/datasets/2010-2020/state/totals
* Defense Manpower Data Center (DMDC) excel https://dwp.dmdc.osd.mil/dwp/app/dod-data-reports/workforce-reports
* Bureau of Economic Analysis apps.bea.gov/histdatacore/HistFileDetails.html?HistCateID=1&FileGroupID=27
* USAFACTS Economy in the United States By State, for Gross Domestic Product (GDP) (Metrics): Data and Trends | USAFacts
* US Regional Economic Analysis Project U.S. Real Gross Domestic Product By State, 1977-2023
* United States Research and Analysis Project https://united-states.reaproject.org/data-tables/gsp-a900n/#
* Population Representation in the Military Services | CNA
* Office of the Under Secretary of Defense, Personnel and Readiness. Population Representation in the Military Services: Fiscal Year 2010-2020.  http://www.cna.org/research/pop-rep.
* US Energy Information Administration https://www.eia.gov/consumption/commercial/maps.php

#### Known Issues and Challenges
* GDPPC calculated manually from US Census population estimates and Bureau of Economic Analysis, which should be the same data over time but because GDP is measured and revised quarterly and annually. 
* GDPPC is measured in calendar years.  All other data is measured in fiscal years. Data may not be 100 % aligned.
* Accessions reported for 1954-1963 include males only; including females would increase accessions by less than 2 percent.  Source: Military data are provided by the Defense Manpower Data Center (DMDC).  Civilian data prior to 1989 measured by calendar years.

