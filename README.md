# Urbanization in California

 This repo is forked from the single repo we used to collaborate for our project. 

Group 5  
Jasleen Kaur  
Ashlee Vo  
Clare Kim  
Lori Bradshaw  

# Project Guidelines

This was our third group project. It took place at 19 weeks into our 26 week bootcamp, so the requirements for success mirrored our increasing knowledge. We chose the Data Visualization Track (other option was Data Engineering Track).  
-Dataset containing at least 1,000 unique records  
-Use of a database such as SQL, MongoDB, SQLite, etc  
-Extensive README file with overview and purpose of project, instructions on how to interact with the project, a discussion on ethical considerations, and data source references  
-A minimum of 3 unique visualizations that are clear and digestible  
-A data story that is easily interpreted by users of all levels  
-Use a Python or JavaScript library now shown in class  
-Some level of user-driven interaction: HTML menus, dropdowns, etc, flash backend with interactive API routes, or visualizations created for user-selected filter criteria  

# Our Topic

Our topic was the effects of urbanization, as defined by population density. We chose to base this analysis on three factors that we felt would be potential negative consequences of population density:  
Homelessness  
Unemployment  
Crime rate  

# Our Data Sources

Time frame: Year of 2019

Our group made a conscious decision to use data from reputable sources. We agreed that this would give us data that is accurate, not skewed, and store in a secure manner. The data we used is anonymous, containing no personal identification or details. 

Another factor to consider in this project was that the data displayed large variances in their average population densities so grouping had to be done in order to accommodate this. 
All 58 counties in California divided into groups based on people per square mile:  
Upper: 2,260 - 18,760
Upper Middle: 460 - 1,700
Middle: 104 - 370
Lower: 2-10

Sources:

Population density information
    https://worldpopulationreview.com/states/california/counties

Statistics on Homelessness
    https://data.ca.gov/dataset/homelessness-demographics

Statistics on Crime Rates
    https://www.ppic.org/data-set/crime-rates-in-california/https://www.ppic.org/data-set/crime-rates-in-california/

Statistics on Unemployment
    https://data.ca.gov/en/dataset/local-area-unemployment-statistics-laus/resource/

# Our Initial Plan

Urbanization = Population Density.  
Rationale: Urbanization involves migration from rural areas to urban areas and subsequent population growth.  
We assumed that with urbanization there will be higher rates of unemployment, homelessness, and crime rate.  
Tools:Python, JavaScript, Tableau  

# Our Project Goal

Our goal is to visualize and break down the effect of the urbanization in California in three main aspects: homelessness, unemployment, and crime rate.   
Issues above persist in the most urbanized areas, affecting thousands of people could push legislation to realize how prominent these issues are in urban areas and increase attention on running social programs and improvements in city planning.  
We chose California because California exhibits a wide range of urban and rural settings, diverse economy, and has the largest population in the US (robust sample size). 

# Project interaction

An interactive map was created using JavaScript. The pink markers represent the county density, the white show total population. Users adjust the view by toggling the options on and off. Users also have an option for a street map or topographic map layer to view the county data.

An interactive pie graph was created in JavaScript to allow users to choose a different graph for each urbanization group using the dropdown menu. They could also hover above each pie slice to view the specific number of occurrences of each crime type.
