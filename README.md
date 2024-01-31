# Data Visualisation using Tableau
 ## Crime Rate data analysis in Brazil

### Dashboard 1: Incident Count
Horizontal Bar Chart on the top shows the incident count in different neighbourhoods. The tree map on the bottom left corner shows the incident count for each type of offence. The Symbol map on the bottom right corner shows the number of incidents that took place in each incident address. My dashboard has the ability to mouse-over the graphs and see the number of incidents that occurred in different neighbourhoods. When clicked on one part of the graph, it drills aggregates and drills down to the number of incidents that took place in each incident address, neighbourhood ID as well as the offense ID. 

 ![image](https://github.com/rpriyaj/Data-Visualisation-using-Tableau/assets/77479366/a7ef64b3-eda4-455a-85ae-c9af4eb13826)

### Dashboard 2: Neighbourhood Demographics (1)
Bar Chart on the top left corner shows the total number of households in each neighbourhood. The bubble chart on the top right corner shows the number of males and females in each neighbourhood. The bar chart on the bottom left corner shows the population which is enrolled in school and the population which Is not enrolled in school. The symbol map on the bottom right shows the average family income in different neighbourhoods. My dashboard can use to see the total number of households in each neighbourhood, the number of males and females in each neighbourhood, the population of people which is enrolled in school and to see the average family income in different neighbourhoods. When clicked on the bar chart as well as the bubble chart, the action allows the user to view the values by aggregating and drilling down to the neighbourhood.

![image](https://github.com/rpriyaj/Data-Visualisation-using-Tableau/assets/77479366/90e9e0e3-0d8f-4220-892f-246dff32ff86)

### Dashboard 3: Neighbourhood Demographics (3)
Symbol map on the top shows the count of different races in all the neighbourhoods. The horizontal bar chart on the bottom left corner shows the age count in all the neighbourhoods. The side-by-side bar chart on the bottom right corner shows the race count for each offense category. I used the sort function to sort the race and offence category by the highest committed offence by the race which committed it. When the user navigates the dashboard, the user is able to mouseover to see the count of each race in every neighbourhood. For that symbol map, users are able to see the individual race count for each neighbourhood by zooming and panning.

![image](https://github.com/rpriyaj/Data-Visualisation-using-Tableau/assets/77479366/c3115725-c549-4af7-8bd5-07ccdff5e012)

### Dashboard 4: Time Series Analysis (4) 
Line chart on the top left corner shows the count of incidents which were reported, in years. The bar chart on the top right corner shows the number of records according to quarters, in all the years. The crime rate can be seen based on quarters in years, where there is an uptrend in the 3rd quarter of every year and a drop in number of records in the 4th quarter of every year. The line chart at the bottom shows the count of incidents which were reported, in months.  I used the custom date function to extract the years, months and quarters from the reported date column. This function allows users to drill down to see which year, month and quarter had the most number of incidents reported. As for the bar chart, when user mouse overs the contents of the bar chart, users will be allowed to see which quarter in each year, has the highest number of records.
![image](https://github.com/rpriyaj/Data-Visualisation-using-Tableau/assets/77479366/b35af7d8-21ce-40d8-af04-f033403fc982)


### Findings and recommendations

#### Findings and Recommendations from Dashboard 1:

|Findings                                                   |  Recommendations 	|
|---	|---	|
|“Five Points” has the most number of incidents (23,441)   	|Take it down as a crime hotspot and find out the underlying reasons on the large incident count in the neighbourhood   	|
|“Traffic Accident” has the most number of incidents (116,690)| Enforce stricter rules to follow when it comes to observing safety on the roads. Example can be to stay 1 car length away.|
|Highest Number of incidents at “E COLFAX AVE/ N WOLFF ST” (134)| 	Place tighter security at that address, increase the number of officers put for patrol duty.|

#### Findings and Recommendations from Dashboard 2:
| Findings  	|  Recommendations 	|
|---	|---	|
| “Capitol Hill” has the highest number of households (567,004,319)	  	| More likely for crimes to take place, hence increase the frequency of the patrols in a day and track the crime rate in the neighbourhood every week.  	|
|There are more people who are not enrolled in school compared to those who are enrolled   	| Pass a compulsory school law which will in turn boost education and reduce crimes.  	|
|The average family income in Auraria is the lowest compared to that of other neighbourhoods | More likely for crimes such as robbery to take place, hence include financial schemes to help residents living in that neighbourhood.|

#### Findings and Recommendations from Dashboard 3:
|  Findings 	|Recommendations   	|
|---	|---	|
|  The “White” people have caused the highest number of traffic accidents compared to other races. 	|  Increase the amount of fines that they have to pay. Through that, they would be more cautious. 	|
|“Montbello” has the highest number of children aged from 0-9 and 10-19, compared to that of other neighbourhoods   	|  Ensure that children are not exposed to the crimes that happen in the neighbourhood, hence, involve children in community activities such as youth clubs, sports groups. 	|

#### Findings and Recommendations from Dashboard 4:
|  Findings 	| Recommendations   	|
|---	|---	|
| There is a sudden decrease in the reported incident count from January to February because only first 2 weeks of the data was collected for February.  	|  This will likely result in inaccuracy because the data was not sufficient enough to tabulate the reported incident count for February, hence tabulate data for the whole month. 	|
|Number of records in the 3rd quarter of the year is always the highest.   	| 	Allocate more officers for duties in the 3rd quarter of the year.  	|


