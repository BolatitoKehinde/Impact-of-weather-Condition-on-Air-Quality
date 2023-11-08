# Impact-of-weather-Condition-on-Air-Quality
IMPACT OF WEATHER CONDITIONS ON AIR QUALITY
ABOUT PROJECT
 
A company in the environmental consulting industry is seeking to understand the dynamics of different weather conditions in a Beijing and the impact on air quality. The goal of the project is to obtain adequate insight from the analysis that can serve as foundation for making recommendations to the government and businesses in the region on how to mitigate the impact of weather conditions on air quality, allow informed decision making for emergency response plans and the preparation for potential air quality issues.

ABOUT DATA

This data set was sourced from the Machine Learning Repository of University of California, Irvine Beijing PM2.5 Data Set (UC Irvine).
The data set contains 43824 rows and 13 columns. The data time is five-year period Jan 1, 2010 – Dec 31, 2014). 
Column definition
Year 
Months
Days
Hours
Pm 2.5 – PM2.5 concentration (ug/m^3); concentration of air pollutant 
DEWP – Dew Point
TEMP – Temperature 
PRES - Pressure
CBWD – Combined Wind Direction 
LWS – Cumulative wind speed
LS – Cumulative hours of snow
LR – Cumulative hours of rain.

According to [Department of Health, New York]; 

Fine particulate matter (PM2.5) is an air pollutant that is a concern for people's health when levels in air are high. PM2.5 are tiny particles in the air that reduce visibility and cause the air to appear hazy when levels are elevated. From Breeze Technologies, the levels of PM2.5 have been grouped to determine the air quality status

-	Excellent (0 - 7): 
-	Fine (7 - 15): 
-	Moderate (15 - 30): 
-	Poor (30 -55): 
-	Very Poor (55 - 110): 
-	Severe (110 >):

ANALYSIS PROCESSES 
The dataset was viewed and cleaned on excel spreadsheet to have an overview of the entire data, and explore possible insights from the data. After the possible insights was noted, the dataset was imported into Tableau to create charts and dashboard in for proper derivation of insights.

Findings

-	Based on yearly average of the air concentration level, 2010 & 2013 has an average of above 100U/gm3, 2011 & 2014 come very close to an average of 100U/gm3. 2012 is around 90Ug/m3. This indicates that the concentration level of pm 2.5 in the city is in a very poor state per the grouping stated above.
-	It is observed that the PM2.5 levels is higher at the start of the year and towards the end of the year which is further proven by higher levels of PM2.5 during the Winter season (December, January and February) and in the Autumn Season (September, October and November)
-	Considering the speed of wind, It is indicated that when the Wind speed is very low, there is high PM2.5 level. Therefore, the lower the wind speed, the higher the concentration of air pollutant. In addition, for Wind direction; the pm 2.5 concentration is highest at calm and stable Wind and lowest when the wind direction is NW
-	The relationship between the pm 2.5 and temperature isn’t of much significance as the concentration is relatively high at all temperature except for extreme instance of < -20’ and > 40’
-	For cumulative hours of rainfall and snow, it is observed that higher the cumulative hours of rainfall and snow, the lower the concentration of pm 2.5 and vice versa.

CONCLUSION
The average concentration of particulate matter (pm 2.5) in the air as revealed by the analysis, far exceeds the annual average deemed fit by the National Ambient Air Quality Standard which stands at 12ug/m3. The lowest average is 90.55ug/m3 in 2012.

The analysis reveals that weather/climate conditions have effects on the the level of pm 2.5, but the dynamics of the result confirms that human factors such as residential wood combustion, car exhaust, and other air pollutants have huge impact on the pm 2.5 level.

RECOMMENDATION

The PM2.5 concentration was seen to rise quickly throughout the winter months. This may be due to the extensive use of coal and other fossil fuels in the production of heat. Therefore, there is an urgent need for the reduction on reliance on coal from industries and during the winter season, limitation of car emissions, and expansion of the production of renewable energy sources, and strictly enforcing emissions regulations. 

Therefore, Policies should be put into place to reduce air pollution by all factors, and energy conserving methods should be applied to day-to-day activities by residents of the city. Where possible, it is advised that there should be replacement of biomass fuels, such as wood, animal dung, and crop wastes, or coal, in homes that use them for cooking and heating with cleaner fuels, including biogas (methane), liquid petroleum gas (LPG), electricity, or solar cookers.

The city should also invest in Mass transportation and Non-motorized transportation system to reduce car emissions.
	
