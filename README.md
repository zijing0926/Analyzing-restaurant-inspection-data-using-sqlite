# Analyzing-restaurant-inspection-data-using-sqlite
This project utilize sqlite to clean and join different datasets to conduct extensive analysis on New York restaurants’ health 
and safety scores and violations. The sample code includes cleaning and joining datasets, applying aggregate functions on scores 
and violations in different zipcode, borough and cuisine. 

Specifically, this project first removes the null entries grouping two varibles.

Second, this project checks the average inspection score for the most recent inspection by zipcode by merging datasets with certain 
conditions, and map it on Carto https://zzhu0926.carto.com/builder/4e424589-44ec-4d28-85c6-53bf0f418476. 

Third, this project checks the average inspection score by different borough in New York. 

Lastly, this project examines the violations by different cuisine. It is important to normalized the number of violation 
by the years of opening for each resturant before taking the average of violation by cuisine. 

This projectalso checks the specific violations by cuisine to find out which cuisines tend to have a disproportionate number of what kind of violation.
The right quantity to look at is the conditional probability of a specific type of violation given a specific cuisine type and divide it 
by the unconditional probability of the violation for the entire population.
