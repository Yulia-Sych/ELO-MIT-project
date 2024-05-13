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

## Key findings

* Analising the data we can see that almost every state had incidents with gun violence. 
* Only 10 states did not have mass shooting cases: Alaska, Delaware, Idaho, Montana, New Hampshire, North Dacota, South Dacota, Vermont, West Virginia, Wyoming.
* Top 3 states with the highest level of mass shooting are California, Texas and Flofida. 
* Noticeable that all states with no incidents are locaten on the North, and states with the highest level of mass shooting are located on the South. 
* Data show that quantity of mass shooting incredibly increase every year. Exclusion is 2020 and 2021 years that connected with Coronovirus pandemic.
* Main part of gun that was used in the mass shooting accident was obtained legally. 23,4% of gun was obtained illegally.
* Quantity of victins significally increasing during the time from less than 50 per year on 80s to more than 150 every year with the case of 700 victims since 2015 up to current time.
* Gathered all data about shooters we can provide a portrait of an average shooter. It's a white man in the age between 21 and 50, most likely 21-30, with previous sign of mental health issues, but he still were able to obtain the gun legally in most cases.

## Action needed
t goes beyond the mass shootings that grab the nation’s attention. Every day, gun violence takes lives from communities all across the country in the form of suicides, unintentional shootings, and interpersonal conflicts that become fatal due to easy access to guns.
There is no single, simple solution to reducing gun violence in this country. But actions needed as a starting point.

1. Sensible gun laws: Reduce easy access to dangerous weapons.
2. Reduce firearm access to youth and individuals who are at risk of harming themselves or others.
3. Insist on mandatory training and licensing for owners.
4. Require safe and secure gun storage.
5. Mental health and wellbeing: Invest in communities to promote resilience and mental health and wellbeing.

