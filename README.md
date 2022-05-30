# Tableau-Challenge-Final

My Tableau Public files can be found using [Q1_2022-citibike_v_5_Offical_Maps_and_2_Dashboards] (https://public.tableau.com/authoring/Q1_2022-citibike_v_5_Offical_Maps_and_2_Dashboards/CityOfficialRequestedMaps-Advanced#1).

My Supporting files can be found using [GitHub] 
(https://github.com/BZNUDS/Tableau-Challenge-Final ).

The data sets I have been using has changed numerous times since I started working on this homework back in early May. Working with my awesome Teaching Assistant Mohamed Hamza, we set-up Python/Pandas code to combine numerous files from the last year. However, the resulting file was too large for Tableau Public to handle. At that time, my always helpful Tutor Yuri Groza suggested I use Tableau Desktop version instead since it is faster and can handle data better. So I started down that path next, but ran into two issues. One was that the Homework instructions say we should submit using Tableau Public. The second issue was Tableau Public limits the files sizes. Therefore, working with both my TA and Tutor and my desire to use the latest data available (as hinted at in the homework instructions), I decided to use the 2022 first quarter data (aka January, February and March) for New York and Jersey City data sets. There are enough trends and phenomenon’s that can be  determined with this data, so in the end it works well.   

# My summary of how I adhered to the Rubric for Citi Bikes Analytics: 
## Discovered Phenomenon Visualizations. I am submitting my Tableau workbook (Q1_2022-citibike_v_5_Offical_Maps_and_2_Dashboards) which includes all of the following:
✓ 11 total visualizations (I know we only needed to do 4-10, but one that I added at the last minute (called Count of Monthly Rides) wasn't very significant, but I thought it would be helpful with showing a trend on the Bike Usage Metrics Dashboard. It did...and I didn't want to throw away any of my prior work:) 
✓ A total of 2 dashboards. One is called "Dashboard of Bike Usage Metrics"  and the other is called "Dashboard of Most/Least Popular Stations" (1 for each phenomenon) 
✓ Data is cleaned (i.e. No outliers or bad data, Nulls removed)
✓ Visualizations can logically be used to discover the solved phenomenon (i.e. they are not just random visualizations) 	


## City Official Requested Maps. ADVANCED Visualization includes all of the following:
✓ Mapped all bike stations
✓ Station markers indicate popularity by size of the filled in circle.
✓ Ability to change marker data based on month and year
✓ Sections are marked by zip code
✓ A write-up on the trends that were discovered while making the map


## Presentation. The Tableau story includes all of the following:
✓ Phenomenon visualizations
✓ Phenomenon dashboards
✓ One of the city official’s requested maps
✓ Arranged in a logical order (i.e. Visualizations for each phenomenon with each other, not all mixed up.) 



# City Official Requested Maps Advanced
<img width="956" alt="City Official Requested Maps Advanced" src="https://user-images.githubusercontent.com/96028923/171048876-c5e5afee-78bc-4d3c-86af-eda498661a80.png">
I did the ADVANCED criteria to get the best grade possible, which includes for the ability to change marker data based on month and year. However, I also think it really helps tell the greater story. 
One of the trends that I observed by creating this was the popularity of the bike stations around the Manhattan area and the overall lack of usage of bike stations the further you get away from these key areas. While not every station falls into this category, several of the key ones do. This analysis is further supported/documented by the "Dashboard of Most/Least Popular Stations". Another interesting trend is the use of Jersey City bike stations. While they don't make the top 10, they definitely have several stations that are more commonly used than others...just like the trend seen in NY City. 


# Dashboard of Bike Usage Metrics
<img width="956" alt="Dashboard of Bike Usage Metrics_Updated" src="https://user-images.githubusercontent.com/96028923/171053713-985cb11e-3fbc-42ae-b780-33ec6f4b91e6.png">
There are several phenomenon’s that can be observed by reviewing this Dashboard of Bike Usage Metrics. 
First, the two different Bike Usage (Start/End) by Hour of the Day charts 
This aligns with a very traditional beginning and end if a work shift in the USA every weekday (Monday through Friday). Another interesting phenomenon is the bike usage peaks between noon and 7pm on Saturday's and Sunday's. Again, it is very traditional that most workers do not go into an office on Saturday and Sunday in the USA. (see USA Bureau of Labor and Statistics information at https://www.bls.gov/news.release/pdf/work.pdf and https://www.bls.gov/tus/charts/chart11.pdf).
Another phenomenon is the that the Annual Members took over 3.5M rides during this quarter and accounted for 36K hours, however their Average Duration was only about 10 minutes. At the same time, a casual user has the bike in use for almost 2 times that duration. That totally makes sense and many of them are out for a "Casual" ride...not hustling to/from work:)   
Lastly, you can see by reviewing the table in the lower left corner of the dashboard that the trend of monthly ridership increases as the weather gets warmer. Looking at that monthly ride data, January was about 1.08M rides where February increases to 1.27M and March increases to 1.95M. (The average temperature in the New York and New Jersey Area was 31, 37, 45 degrees Fahrenheit in January, February, March respectively in 2022. https://www.timeanddate.com/weather/usa/new-york/historic?month=1&year=2022) 

# Dashboard of Most/Least Popular Stations
<img width="955" alt="Dashboard of Most Least Popular Stations_Updated" src="https://user-images.githubusercontent.com/96028923/171054113-a2baa6cd-87a2-4d40-9e8c-cfcc6336631a.png">
There are a couple of phenomenon's that can be observed by reviewing this Dashboard of Most/Least Popular Stations. The most impressive one to me is how the TOP 9 (out of 10) Start and End stations are a one for match in the rank order details. Additionally, the Count of Rider Ids' are all within 1.5% of each other, Stated differently, there were 20,699 Starts at W 21 St & 6 Ave while there were 20,773 Ends at that same station. This seems logical to me that one would start and stop at the same point each time. 


# Supporting Visualizations Below

Map of Starting Stations
<img width="956" alt="Map of Starting Stations" src="https://user-images.githubusercontent.com/96028923/171049955-e20cea8d-96d9-471d-9766-631045f17739.png">



Map of Ending Stations
<img width="957" alt="Map of Ending Stations" src="https://user-images.githubusercontent.com/96028923/171049996-c6d1b12b-641b-46fe-acf3-b8a5016a5724.png">


Bike Usage Start by Hour of the Day
<img width="950" alt="Bike Usage Start by Hour of the Day" src="https://user-images.githubusercontent.com/96028923/171050045-fb0ee45e-96d9-4968-932a-9117ab1ec699.png">


Bike Usage End by Hour of the Day
<img width="947" alt="Bike Usage End by Hour of the Day" src="https://user-images.githubusercontent.com/96028923/171050091-5668028f-0dfc-4f92-b520-e70bec0f84a1.png">


Length of Rides
<img width="949" alt="Length of Rides" src="https://user-images.githubusercontent.com/96028923/171050134-2f62bbc9-1191-4716-bd2b-ce2083518de0.png">


10 Most/Least Popular Starting Stations
<img width="947" alt="10 Most Least Popular Starting Stations" src="https://user-images.githubusercontent.com/96028923/171050191-25e522da-7c49-43ff-be40-6aa11d455ef4.png">


10 Most/Least Popular Ending Stations
<img width="950" alt="10 Most Least Popular Ending Stations" src="https://user-images.githubusercontent.com/96028923/171050219-7e6fc2cb-ae51-4e5f-bb25-e69d4581d1a0.png">


Map of 10 Most Least
<img width="945" alt="Map of 10 Most Least" src="https://user-images.githubusercontent.com/96028923/171050317-2dd41800-5828-4e73-bfad-0861e8d5ffb3.png">


Map of 10 Most Starts
<img width="930" alt="Map of 10 Most Starts" src="https://user-images.githubusercontent.com/96028923/171050381-fdd79aee-95f2-4ba0-9ea7-dde429e08ed9.png">


Map of 10 Least Starts
<img width="941" alt="Map of 10 Least Starts" src="https://user-images.githubusercontent.com/96028923/171050450-1631c588-11d7-4400-9aa2-9fc0a3e55c52.png">




