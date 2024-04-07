# tableau_challenge

The purpose of thhis assignment is to aggregate the data found in the Citi Bike Trip History Logs and find unexpected phenomena.

**Data Source**
https://citibikenyc.com/system-data

**Tableau Workbook**
https://public.tableau.com/views/TableauChallenge_17125218924390/CitiBikeDataanalysis2023?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link

**Story**

For this analysis I've taken CitiBike dataset of 2023 year. Files for all months were merged into one CSV file using Pandas. The CSV file generated in the Jupyter Notebook was loaded into Tableau as the only data source.

**Step 1**
I built a bar plot illustrating total number of rides taken in 2023 and split by months. The most number of trips (over 100k) falls into summer minths July-August when it's a seson of school holidays and vacations.

<img width="452" alt="Raw data" src="https://github.com/askarovamari/tableau_challenge/blob/main/Total%20number%20of%20rides.png">


**Step 2**
A map is built that plots all bike stations with a visual indication of the most popular locations to start and end a journey. As shown in the analysis, 9 locations were identified as the most popular for starting and ending trips.

<img width="452" alt="Raw data" src="https://github.com/askarovamari/tableau_challenge/blob/main/Map.png">
<img width="452" alt="Raw data" src="https://github.com/askarovamari/tableau_challenge/blob/main/Top%2010%20bar%20chart.png">


**Step 3**

Further in the anlaysis, I sliced data by user and bike types to unveil trends. As it's shown on the chart below, most of the users preferred riding classic bikes to electric ones in 2023. We can assume that members/subscribers are in favor of dockless bikes as there is no data indicating any rent of docked bikes by members.

Although, classic bikes are the top choice based on the number rides, it looks like duration of trips is longer when users rent electric bikes or docked bikes in case of guest/casual users.

<img width="452" alt="Raw data" src="https://github.com/askarovamari/tableau_challenge/blob/main/Metrics%20per%20user_bike%20type.png">


**Step 4**

Diving into the data, I analyzed trand of hours when bikes are rented based on seasons of the year. One common trend that is being observed throughout the year is that 8 am and 6 pm are the peak hours as it links to rush hours, when most of the people commute to work/school. However, comparing the winter and summer graphs we can coclude that Number of rides is obviously rising towards summer and then dropping closer o winter time. That is most likely driven by weather conditions in New York.

<img width="452" alt="Raw data" src="https://github.com/askarovamari/tableau_challenge/blob/main/Peak%20hours%20by%20seasons.png">
