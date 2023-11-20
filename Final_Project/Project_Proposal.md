# <div align="center">Comprehensive Analysis of Air Quality in New York City</div>

## <div align="center">Project Proposal</div>

### <div align="center">Yaren Benhür</div>

### 1. Introduction:
Air pollution stands out as a critical environmental threat to urban populations. While everyone is subject to exposure, there exists variation in pollutant emissions, levels of exposure, and population vulnerability among different neighbourhoods. The repercussions of exposure to common air pollutants are extensive, encompassing links to respiratory and cardiovascular diseases, cancers, and premature deaths. New York City, being one of the world's most densely populated urban centers, grapples with persistent challenges regarding air quality, exerting a significant impact on the health and well-being of its residents. The presented indicators offer a temporal and geographical perspective to comprehensively characterize air quality and health trends in NYC. The objective of this project is to conduct a thorough analysis of air quality in the city. 


### 2. Objectives:
The primary objectives of this project are multifaceted, requiring a comprehensive approach to understanding the dynamics of air quality in NYC. Employing a multifaceted approach that integrates data from various sources, I aim to explore the intricate interplay between traditional air quality indicators, forestry tree density, building density, industrial activities, and traffic density. I will mainly use the website NYC Open Data for receiving data. Also, NYC Department of Health provides data source of real-time air quality which is good for making hourly comparisons.  
  
Not only the reasons also estimated health impacts of air pollution will be considered. It is an important environmental threat to the health of New York City residents. Exposures to two common air pollutants, fine particulate matter (PM2.5) and ozone (O3), can worsen respiratory illness and heart conditions and contribute to premature deaths. Older adults, children and people with existing heart and lung disease are especially affected.  
  
Fine particulate matter, also known as (PM2.5), are small airborne particles that can be inhaled deep into the lungs. Major sources of PM2.5 include trucks, buses and cars, and the burning of fossil fuel to generate electric power and heat buildings. Exposure to particulate matter has been linked to breathing problems, reduced lung function, heart disease and premature death. Ozone, also called smog, causes irritation and inflammation of the lungs and worsening of asthma. For that I plan to get hospitalization and death rates to calculate the health impact associated with the change in air quality in each neighbourhood. 
The ultimate goal is to provide nuanced insights that can inform decision-making processes and potentially guide policy interventions.  
  
**Industrial Analysis:** 
The amount of industrial area in a neighbourhood may affect its air quality in several ways. Manufacturing may emit pollutants, construction can kick up particulate matter, and increased truck traffic can lead to increased vehicular emissions. Obtaining detailed data on industrial activities in different NYC neighbourhoods, encompassing the types of industries, emission levels, and specific pollutants associated with each industrial sector.  
**Traffic Density Exploration:** 
Traffic density affects a neighbourhood’s air quality in a few ways. Combustion engines emit "tailpipe emissions" such as PM2.5, NOx and carbon monoxide (CO), while dust from wear to tires and from braking contribute additional particulate matter to the air. Fetching data on traffic density, focusing on vehicular emissions and traffic-related pollutants. This will involve collaboration with city traffic management sources and other relevant databases.  
**Forestry Tree Points:**
The project includes the integration of forestry data, incorporating information on urban green spaces, tree cover, and forestry management practices. This expansion aims to explore the role of urban forestry in influencing air quality and public health. The project integrates forestry data to assess how urban trees and greenery contribute to mitigating pollution. This objective aligns with the broader goal of understanding the interconnectedness of urban ecosystems.  
**Health Data:**
This objective involves fetching and integrating health-related data, including information on diseases such as asthma and other relevant health indicators. The goal is to correlate health data with environmental factors, providing insights into the broader health implications of the urban environment. This step aims to uncover correlations between air quality, industrial activities, traffic density, and prevalent health conditions, contributing to a holistic understanding of urban well-being.


### 3. Methodology:
The methodology for this project encompasses a series of meticulously planned steps to ensure the accuracy and reliability of the results:  
  
Data Acquisition: The project will utilize a combination of web scraping and API calls to extract data from the identified websites. This involves designing robust scripts to navigate through the web interfaces and retrieve relevant information.
  
Data Integration: The different datasets obtained from the air quality dataset, industrial sources, and traffic management databases will be merged to create a unified dataset. The integration process involves aligning data points, handling inconsistencies, and creating linkages between different data sources.  
  
Data Cleaning: A detailed data cleaning process will be implemented to address missing values, outliers, and format inconsistencies. This step is essential to ensure the accuracy and reliability of the subsequent analyses.  
Exploratory Data Analysis (EDA): EDA will involve statistical analysis and visualization techniques to identify patterns, correlations, and trends within the integrated dataset. This phase aims to provide a preliminary understanding of the data distribution and relationships.  
   
Spatial and Temporal Analysis: The spatial and temporal aspects of the data will be explored using geospatial visualization tools and time series analysis. This involves mapping air quality indices, industrial activities, building and traffic density to geographical locations and exploring how these variables change over time.



### 4. Data Sources:
The richness of this project lies in its ability to harness data from various sources, ensuring a holistic understanding of the factors influencing air quality in NYC:  
  
#### 4.1 NYC Air Quality Dataset: 
This serves as the foundational dataset, providing traditional air quality indicators measured across different regions of the city. The dataset that will be used listed below.    
  
1.https://a816-dohbesp.nyc.gov/IndicatorPublic/AQHub/realtime.html (NYC)  
2.https://data.cityofnewyork.us/Environment/Air-Quality/c3uy-2p5r (Real-Time)  
3.https://www.epa.gov/aqs (USA all states)  
  
The first dataset will be used mainly, I’ll consider other two if they needed. Data is provided by Department of Health and Mental Hygiene (DOHMH). It is made public at 2014. The information about this data explained below.  
  
**Outdoor Air Pollutants**  
Estimated annual average concentrations calculated from a model that used NYC Community Air Survey measurements.  
  
• Fine Particulate Matter (PM2.5) Fine particles are emitted by vehicles, building boilers, and other combustion - and are a major form of air pollution that harms health.  
• Nitrogen Dioxide (NO2) Nitrogen oxides (NOx), which include nitric oxide (NO) and nitrogen dioxide (NO2), are a group of pollutants formed by combusion that can cause damage to lung tissue, breathing and respiratory problems, as well as contribute to smog and acid rain.  
• Sulfur Dioxide (SO2) Sulfur dioxide comes from burning certain types of fuel oil. As an air pollutant, it can can worsen lung diseases.   
• Ozone (O3) Ozone is a common air pollutant that can harm breathing and worsen asthma and other respiratory conditions.   
  
**Outdoor Air Toxics**  
Estimated annual average concentrations of known carcinogens that are part of a class of pollutants also known as hazardous air pollutants.  
  
• Air Toxics Concentrations- Average Benzene Concentrations Benzene is an air pollutant resulting from motor vehicle and  industrial emissions and tobacco smoke. Benzene is a known carcinogen that can also harm bone marrow and red blood cell function.  
• Air Toxics Concentrations- Average Formaldehyde Concentrations Formaldehyde is an air pollutant resulting from car exhaust and the manufacture of industrial products. Formaldehyde is a known carcinogen that can also cause irritation to eyes and lungs and increase risk of asthma and trigger asthma symptoms.  
  
**Traffic Density**  
Estimated millions of annual vehicle miles travelled per km2. Vehicle miles travelled is an indicator of emissions from automobile exhaust, brake wear and tire wear.  
  
• Traffic Density- Annual Vehicle Miles Travelled Traffic density is a measure of the average number of vehicles that occupy specified area. Traffic density can influence health as a source of air pollution and traffic-related injuries.  
• Traffic Density- Annual Vehicle Miles Travelled for Cars Traffic density is a measure of the average number of vehicles that occupy specified area. Traffic density can influence health as a source of air pollution and traffic-related injuries.  
• Traffic Density- Annual Vehicle Miles Travelled for Trucks Traffic density is a measure of the average number of vehicles that occupy specified area. Traffic density can influence health as a source of air pollution and traffic-related injuries.  
  
**Heating Fuel Emissions**  
Estimated annual boiler emissions per km2 as of January 2015. Calculated using heating fuel type on NYC boiler permits and estimates of boiler activity.  
  
• Boiler Emissions- Total SO2 Emissions Boilers are a common source of SO2,which can worsen lung disease.  
• Boiler Emissions- Total PM2.5 Emissions Boilers are a common source of PM2.5, which can harm health.  
• Boiler Emissions- Total NOx Emissions Boilers are a common source of NOx emissions, which can harm health.   

**Columns (Fields, Attributes):**  
  

|Column Name|	Column Description|
|-----------|---------------------|
|unique_id|	Unique record identifier|
|indicator_id|	Identifier of the type of measured value across time and space|
|name|	Name of the indicator|
|measure|	How the indicator is measure|
|measure_info|	Information (such as units) about the measure|
|geo_type_name|	Geography type|
|geo_join_id	|Identifier of the neighborhood geographic area, used for joining to|mapping geography files to make thematic maps|
|geo_place_name|	Neighborhood name|
|time_period |	Description of the time that the data applies to|
|start_date|	Date value for the start of the time_period|
|data_value	|The actual data value for this indicator, measure, place, and time|
|message|	Notes that apply to the data value|


#### 4.2 Health Datasets:
Health data consist of 7 different data sources from 2005 to 2017. Which are  
  
**1. Emergency Department Visits:**  
•	Asthma emergency departments visits due to Ozone  
(https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/health-impacts-of-air-pollution/?id=2122#display=summary)  
•	Asthma emergency departments visits due to PM2.5  
(https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/health-impacts-of-air-pollution/?id=2117#display=summary)    
  
**2. Hospitalizations:**  
•	Asthma hospitalizations due to Ozone  
(https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/health-impacts-of-air-pollution/?id=2124#display=summary)  
•	Cardiovascular hospitalizations due to PM2.5 (age 40+)  
(https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/health-impacts-of-air-pollution/?id=2120#display=summary)  
•	Respiratory hospitalizations due to PM2.5 (age 20+)  
(https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/health-impacts-of-air-pollution/?id=2119#display=summar)  
  
**3. Deaths:**  
•	Cardiac and respiratory deaths due to Ozone  
(https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/health-impacts-of-air-pollution/?id=2121#display=summary)  
•	Deaths due to PM2.5  
(https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/health-impacts-of-air-pollution/?id=2108#display=summary)  
  



#### 4.3 Forestry Tree Points Dataset
https://data.cityofnewyork.us/Environment/Forestry-Tree-Points/hn5i-inap  
  
Data provided by Department of Parks and Recreation. Record of Forestry tree points for NYC Parks & Recreation. Tree Points and Planting Spaces form the basis of ForMS 2.0’s data inventory and are the core entities that all Service Requests, Inspections, and Work Orders are associated to.  
  
**Columns (Fields, Attributes):**  
|Column Name|Column Description|
|-----------|------------------|
|OBJECTID|	Unique identifier for each tree point|
|DBH|	Diameter of tree at breast height (4.5 feet off the ground)|
|TPStructure|	Indicates the current physical state of the tree (stump, shaft, or entire tree intact)|
|TPCondition|	Indicates condition of the tree based on biological health and physical structure|
|StumpDiameter|	Diameter of exposed stump face|
|PlantingSpaceGlobalID|	Unique identifier for planting space associated with tree point|
|Geometry|	Geometry for planting space in well-known text|
|GlobalID|	Unique identifier for each tree point|
|GenusSpecies|	Tree species, includes gensus and specific epithet plus common name|
|CreatedDate|	Date tree point record was created|
|UpdatedDate|	Date tree point record was last updated|
|PlantedDate|	Date tree was planted|
|RiskRating|	Risk rating of the most recent risk assessment inspection|
|RiskRatingDate|	Date of most recent risk assessment inspection|
|Location	||


### 5. Project Timeline:
A meticulously planned timeline ensures the project progresses efficiently and meets its objectives within the specified timeframe:  
  
Week 1: Data fetching and pre-processing. This involves scripting for web scraping, API calls, and initial cleaning processes.  
Week 2: Exploratory data analysis and visualization development. This phase will delve into the data's nuances and provide preliminary insights.  
Week 3: Integration of industrial and traffic-related data. Merging datasets to create a comprehensive dataset that incorporates air quality, industrial, and traffic-related information.  
Week 4: Statistical analysis and correlation assessments. Conducting advanced statistical analyses to identify correlations and trends within the integrated dataset.  
Week 5: Dashboard development and finalization. Creating an interactive dashboard that allows stakeholders to explore the integrated dataset dynamically.  


### 6. Conclusion and Impact:
In embarking on this ambitious endeavour to comprehensively analyse the environmental landscape of New York City, my project has traversed diverse domains, integrating data on air quality, industrial activities, traffic density, public health, and urban forestry. The multifaceted nature of our objectives speaks to the complexity of urban ecosystems and the need for a holistic approach to understanding the interplay of various factors shaping the environmental and public health landscape.  
  
As I reflect on the questions that have guided our exploration, several key inquiries have driven our methodology:  
How do industrial activities impact air quality, and what are the potential health ramifications? Through detailed industrial analysis, I seek to unravel the intricate relationship between industrial emissions and air quality. Questions about the health implications of these emissions underscore our commitment to exploring not only environmental factors but also their broader public health repercussions.  
  
What is the relationship between traffic density, vehicular emissions, and public health outcomes? My expanded exploration of traffic density goes beyond traditional air quality considerations. By integrating health data, I aim to discern correlations between transportation-related pollutants and prevalent health conditions, providing insights into the broader health implications of urban mobility.  

How does the presence of green spaces and urban forestry contribute to mitigating pollution and influencing public health? The integration of forestry data introduces a novel dimension to our analysis. I inquire about the role of urban greenery in influencing air quality and public health, expecting to see correlations between the presence of green spaces and positive environmental and health outcomes.  
  
What patterns emerge when examining the spatial and temporal dimensions of air quality, industrial activities, traffic density, health outcomes, and urban forestry? My spatial and temporal analysis transcends traditional boundaries, encompassing a multidimensional exploration of how these factors evolve across different regions and time periods. I anticipate uncovering patterns and trends that provide a nuanced understanding of the dynamics shaping New York City's environmental landscape.  
  
In expecting results from our holistic analysis, I foresee a synthesis of insights that goes beyond isolated observations. I anticipate a dataset that not only captures the variations in air quality but also reveals correlations between environmental factors and public health outcomes. By integrating health and forestry data, I hope to demonstrate the interconnectedness of urban ecosystems, emphasizing the role of green spaces in mitigating pollution.  



```python

```
