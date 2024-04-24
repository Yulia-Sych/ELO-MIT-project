# Mass Shooting in the USA 
## Problem Identification
The mass shooting problem in the United States is a complex and deeply concerning issue that continues to elicit widespread debate and calls for action.  Despite efforts to address the root causes and implement stricter gun control measures, such as background checks and restrictions on high-capacity magazines, the prevalence of mass shootings persists. The multifaceted nature of this problem involves considerations of mental health, social alienation, access to firearms, and systemic inequalities. Finding meaningful solutions demands a comprehensive approach that addresses these interconnected factors while respecting individual rights and promoting community safety.

## Research questions
1. How many people got killed and injured per year?
2. Visualize mass shootings on the U.S map
3. Is there any correlation between shooter and his/her race, gender
4. Any correlation with calendar dates? Do we have more deadly days, weeks or months on average
5. What cities and states are more prone to such attacks
6. Can you find and combine any other external datasets to enrich the analysis, for example, gun ownership by state
7. Any other pattern you see that can help in prediction, crowd safety or in-depth analysis of the event
8. How many shooters have some kind of mental health problem? Can we compare that shooter with general population with same condition

## Data
To answer research questions was chosed next dataset: US Mass Shootings, 1982–2023: Data From Mother Jones’ Investigation.
The dataset provides a comprehensive collection of information regarding mass shooting incidents in the United States over a period from 1982 to 2023. It includes detailed data points such as 
* Case (str) - name of each case of shooting
* Location - the location (including state and city)
* Date (date) - the date of each incident
* Summary (str) - short description for each case
* Fatalities (int) - the number of fatalities
* Injured (int) - the number of injuries
*Total victims (int) - the number of fatalities and injuries
* Place (str) - where the shooting took place
* Age of shooter (int) 
* Prior Sighns Mental Health Issues (str) 
* Mental health details (str) - short description for mental health condition
* Weapons obtined legally (str) - Yes/No
* Weapon Type (str) - the type of weapons used
* Race (str)
* Gender (str) - the perpetrator's identity
* Sourse (str) - link for the source of the information

This dataset allows for in-depth analysis of trends and patterns in mass shootings over the past four decades, offering insights into factors such as frequency, severity, geographical distribution, and changes over time. Researchers and analysts can utilize this dataset to explore correlations, identify potential risk factors, assess the effectiveness of policy interventions, and inform evidence-based strategies for preventing and mitigating the impact of mass shootings in the future. To find original data please follow the [link](https://www.motherjones.com/politics/2012/12/mass-shootings-mother-jones-full-data/).

## Approach
To explore and clean the data was used Python. [Notebook](https://github.com/Yulia-Sych/ELO-MIT-project/blob/main/Mass_shooting_US_data_preparation.ipynb) with data exploration and cleaning. Cleaned [file](https://github.com/Yulia-Sych/ELO-MIT-project/blob/main/Mass_shooting_US_cleaned.xlsx) saved into xlsx format to work in Tableau for analysis and data visualisation.

