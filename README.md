# SurviveLQ-Analytics-Dashboard
SurvivelQ Analytics Dashboard
Introduction
Story of data
Data splitting and preprocessing
Pre-analysis
In-analysis
Post-analysis and insight
Data visualization and charts
Recommendation and observation
Conclusion
References and appendices

Introduction
This report explores the survival outcomes of passengers using the SurviveLQ Analytics Dashboard. The dashboard provides insights into passenger demographics, ticket class, fare pricing, and survival rates based on various categorical groupings such as age, sex, and deck.
The goal is to understand which factors influenced survival the most, and how patterns in age, class, and gender relate to overall survival. This analysis can be helpful in modeling human behavior, identifying patterns in crisis scenarios, or developing algorithms for predictive survival classification.
Story of the Data
The dataset analyzed in this dashboard is based on a simulated or expanded version of historical maritime passenger records, likely inspired by the Titanic dataset often used in data science projects. It includes:
Key Fields:
Total Passengers: 5 million simulated entries
Total Survived: 1,483 individuals
Survival Rate: ~49%
Passenger Demographics: Age group (adult, child, senior, middle age, teenager), sex
Travel Details: Deck, embarkation point, fare paid per person, ticket class (Pclass)
Purpose:
The data is structured to reveal correlations between passenger characteristics and survival outcomes, making it ideal for:
Classification modeling (e.g., predicting survival)
Behavioral insights during emergencies
Policy simulations (e.g., prioritization strategies in evacuation)
Dashboard Components:
Bar Charts: Breakdown of survivors by age group, passenger class, deck
Pie Chart: Gender-based survival comparison
Treemap: Fare distribution across age groups
Indicators/KPIs: Total survived, top embarkation point (Q), survival rate

DATA SPLITTING AND PREPROCESSING
DATA CLEANING: this is when the data is free from errors dataset ensures accuracy and reliability in analysis and which include;
Removing duplicates
Correcting errors
Standardizing data format
Data Transformations: Transformations were applied to prepare the data for better interpretation and analysis.
Data splitting: This involve the splitting of data point into two category independent and dependent variable.
· Independent variable are those variable that can stand alone i.e your name, and can still make meaning.
· Dependent variable are those variable that can't stand alone they won't make any meaning until they are attached to something e.g revenue, quantity.
And also look at the preprocess like:
Industry type
Story of data
The stake holder of project
What success means to the industry

Potential analysis/question
1. What factors most influenced survival?
2. Did women have a higher survival rate than men?
3. Did 1st class passengers survive more often?
4. Was there a survival advantage for children or seniors?
5. How did traveling alone affect survival?
6. Is there a relationship between fare paid and likelihood of survival?
7. Do specific decks have higher survival rates?
8. Are there patterns between family size and survival?
9. Did port of embarkation affect chances of survival?

Potential Insight
1 Females had much higher survival rates
2 1st Class passengers survived more often, Better access to lifeboats and early evacuation.
3 Children had relatively high survival rates, Reflects rescue priorities.
4 Traveling alone reduced survival chances, Families may have supported each other during the chaos.
5 Higher fares correlated with survival, Fare may reflect access to better locations or assistance.
6 Certain decks had lower survival, Possibly due to being lower in the ship or more crowded.
7 Class and gender were stronger predictors than age or fare

In analysis observation
1. 49.4% of passengers survived overall.
2. About 74% of females survived compared to only 18% of males.
3. 1st Class passengers had a significantly higher survival rate (~62%) than 3rd Class (~24%).
4. Children (under 13) had noticeably higher survival rates.
5. Most passengers in Fare Bin: Low were from 3rd Class and had low survival.
6. Majority of passengers embarked from Southampton (~72%).
7. Only 8.2% of passengers traveled completely alone.
8. Passengers with known cabins were more likely to survive (linked to higher-class tickets).

In analysis insight
1. Gender was the strongest predictor of survival - supporting the "women and children first" evacuation policy.
2. Socioeconomic class played a critical role; those who could afford better cabins had better access to safety.
3. Traveling in a group (not alone) may have improved chances of survival, possibly due to support or visibility.
4. Age-based priority suggests ethical patterns in rescue children were given preference.
5. The Fare variable acts as a proxy for class and survivability higher-paying passengers had better outcomes.
6. Port of embarkation may reflect regional class differences (e.g., 3rd Class boarding from Southampton).
7. Engineering features like HasCabin, IsAlone, and FarePerPerson provide powerful improvements to analysis compared to raw fields.

OBSERVATION
1. Females had a 74% survival rate, far higher than males at 18%Gender was the most significant factor in survival
2. 1st Class passengers had a survival rate above 60%, compared to ~24% for 3rd Class Socio economic status influenced access to lifeboats
3. Children (<13 years) had higher survival rates than teens and adults Age priority was respected in the evacuation process
4. Passengers who traveled alone had lower survival rates Social support may play a role during crises
5. Higher fare-paying passengers survived more, especially in upper decks Fare acts as a proxy for safety access and status
6 Embarkation port (Southampton) had the lowest average survival Majority of 3rd Class boarded there, indicating a demographic risk factor

RECOMMENDATION
1. Prioritize inclusive safety protocols in transport industries, Avoid class-based or social bias in emergency procedures
2. Improve safety access across all travel classes, Ensure fair access to lifeboats and exits regardless of fare/class
3. Design for group awareness in emergencies, Systems should highlight individuals traveling alone for assistance
4. Reinforce child safety prioritization in modern safety drills, Historical precedent proves its effectiveness
5. Monitor and manage class/fare-based risks proactively
6. Use data-driven simulations to improve rescue outcomes, Predictive models can be used in transport planning and training
7. Use engineered features (e.g., IsAlone, FarePerPerson) in predictive models, These add strong analytical value over raw data alone

Conclusion
The SurviveLQ Analytics dashboard provides a comprehensive overview of survival patterns among passengers based on demographic and travel-related factors. With a total simulated population of 5 million passengers and a survival count of 1,483, the overall survival rate stands at 49%, indicating nearly an even split between those who survived and those who didn't.
