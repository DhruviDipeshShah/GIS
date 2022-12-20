## New Brunswick High Injury Network Map
### A project by Rodas Bekele and Dhruvi Shah
#### Guided by Prof. Will Payne and Rithika Rajamohan for the course Command Line GIS

##### The project aims at analyzing crash data in New Brunswick, New Jersey to understand and identify the streets with heavy injuries and fatalities. Clean traffic crash data in New Brunswick, New Jersey is not available to the general public. The New Brunswick Police department makes individual accident reports for certain years available but that would require an extensive amount of time dedicated to data cleaning. We spoke to Hanna Younes and Leigh Ann Von Hagen at the Rutgers Pedestrian and Bicycle Resource center and found out that we can get access to CSV file of clean crash data through the resource center. The traffic crash data we acquired from the center has the crash incidents data for ten years between the year 2011-2021. This data is classified into different types severity, fatality, injury, and property damage. Because we are focusing on human injury and fatalities, we filtered the data to exclude property damage. This resulted in 2,920 incidents of injury and fatalities out of the total 13,011 incidents in the dataset. 
##### In addition to the crash data, we used census data for income, and racial demographics data using the census API. We also acquired the New Jersey road centerlines, which we clipped to New Brunswick, through the NJGIN Open Data website.

<iframe src="Image showing Income Levels.png" height="600" width="1000"></iframe>
##### As seen in the map above, the purple colored census tracts have the lowest income levels in New Brunswick, NJ. This range falls into the range of $26108 to $44594. This is followed by the blue colored census tracts, while yellow shows the highest income levels of $91559 and above. 

<iframe src="Image showing Communities of Concern.png" height="600" width="1000"></iframe>
##### The yellow colored tracts have the highest percentage of communities of color. This percentage lies above 53%. 

<iframe src="Total_Injuries_by_cenus_tract.png" height="650" width="1000"></iframe>
##### Towards the north of New Brunswick, where the yellow color is shown, we have the highest injuries in the city. This census tract also has comparatively low incomes in the city and over 35% racial minorities staying there.

<iframe src="HIN New.html" height="1000" width="1000"></iframe>

You can explore this map [as its own page here](HIN New.html). 
