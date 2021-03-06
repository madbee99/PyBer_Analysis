# PyBer Ridesharing Analysis
I did this project at the beginning of the UC Berkeley Extension Data Analytics Bootcamp. I used Python to create basic plots based on a fictional ride-sharing company's data. Libraries used include Matplotlib, NumPy, and Pandas.

## Overview  
This project analyzes PyBer ride-sharing data to determine the accessibility and affordability of rides in various areas (broken into three categories: urban, rural, and suburban). The data include the date of rides, the city, the city type (urban, rural, suburban), the fare, the total number of drivers, and the ride ID.

## Results
After analyzing and examining the data results among the three city types (urban, rural, suburban), it appears that the average fare per ride is the lowest in urban areas ($24.53/ride) and the highest in rural areas ($34.62/ride). Subsequently, the same ranking applies to the average fare per driver, with an average fare of $16.57 per urban driver, $39.50 per suburban driver, and $55.49 per rural driver. Urban areas have the highest number of rides and drivers, suburban areas have the second highest number of rides and drivers, and rural areas have the lowest number of rides and drivers. The total number of drivers in rural areas is the lowest with only 78 drivers, the second lowest in suburban areas with 490 drivers, and the highest in urban areas with 2,405 drivers. See the dataframe screenshot below for an organized output of these results.

[PyBer Summary Dataframe](analysis/PyBer_Summary_dataframe.PNG):  
![PyBer_Summary_dataframe](https://user-images.githubusercontent.com/86338416/126919200-6152af12-341d-4fff-8569-f3596dd77fe6.PNG)  

The pie charts below provide visualizations of the percent of the total number of PyBer rides and drivers (one chart for rides, one chart for drivers) from January through April 2019, categorized by city type (urban, rural, and suburban). As one can see from the pie charts, there is a strong correlation between the percent of drivers and percent of rides in each city type.   
![image](https://user-images.githubusercontent.com/86338416/164313734-9fe9deed-569b-467a-9325-ad0ce6827545.png) ![image](https://user-images.githubusercontent.com/86338416/164314388-bd691e86-b10f-49f5-a1c8-350e5876d11f.png)   

These results make sense because urban areas tend to be more densely populated, meaning that there would be more people needing rides and more drivers available, which corresponds with urban areas having the highest number of rides and drivers. In contrast, in rural areas there are fewer people, so it again makes sense that there would be fewer riders and drivers, resulting in the lowest number of rides and drivers. Since supply and demand are higher in the urban areas, the fares do not have to be as high as they are in the suburban and rural areas for PyBer to still make a profit from rides in urban areas. The line graph below shows how urban areas consistently produce the most money (total fares) for PyBer and the rural areas consistently produce the least amount of money (total fares), specifically on a weekly basis between January and April of 2019.

[PyBer Total Fares by City Type](analysis/PyBer_fare_summary.png):  
![PyBer_fare_summary](https://user-images.githubusercontent.com/86338416/126919215-92aafd65-a91e-414a-beda-246c71787a1c.png)    

The box-and-whiskers plot below emphasizes how urban areas have the highest number of rides.  
[PyBer Ride Counts by City Type](analysis/Fig2.png):  
![Fig2](https://user-images.githubusercontent.com/86338416/126919315-5e6dd4f1-0821-4ed7-a106-8254ba7236c2.png)  

The scatter plot shows the average fare against the total number of rides in a city, categorized by city type.   
[PyBer Ride-Sharing Data (2019)](analysis/Fig1.png):  
![PyBer Ride-Sharing Data (2019)](https://github.com/madbee99/PyBer_Analysis/blob/main/analysis/Fig1.png)  



## Summary  
Based on the results, it is clear that the ratio of number of drivers to riders is the highest in urban areas and the lowest in rural areas. Some potential ideas to increase PyBer usage in non-urban areas would be to 1) provide first time user discount codes in rural and suburban areas, incentivizing people to use their service, 2) provide bonuses to drivers who give rides in those areas (reallocating some of the current drivers in urban areas to rural and/or suburban areas), and 3) try to hire more drivers who already live in rural areas and will most likely want to stay closer to home, hopefully increasing the number of drivers available in rural areas (although this is a moot point if there are not enough riders in rural areas).  


## Resources
Data provided by UC Berkeley Extension Data Analytics Bootcamp.





