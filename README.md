# PyBer_Analysis
## Overview  
This project analyzes PyBer ride sharing data to determine the accessibility and affordability of rides in various areas (broken into three categories: urban, rural, and suburban). The data includes the date of rides, the city, the city type (urban, rural, suburban), the fare, the total number of drivers, and the ride ID.

## Results
After analyzing and examining the data results among the three city types (urban, rural, suburban), it appears that the average fare per ride is the lowest in urban areas ($24.53/ride) and the highest in rural areas ($34.62/ride). Subsequently, the same ranking applies to the average fare per driver, with an average fare of $16.57 per urban driver, $39.50 per suburban driver, and $55.49 per rural driver. See the dataframe screenshot below for an organized output of these results. These results make sense because urban areas tend to be more densely populated, meaning that there would be more people needing rides and more drivers available, which corresponds with urban areas having the highest number of rides and drivers. In contrast, in rural areas there are fewer people, so it again makes sense that there would be fewer riders and drivers, resulting in the lowest number of rides and drivers. Since supply and demand are higher in the urban areas, the fares do not have to be as high as they are in the suburban and rural areas for PyBer to still make the most money from rides in urban areas. The line graph below shows how urban areas consistently produce the most money (total fares) for PyBer and the rural areas consistently produce the least amount of money (total fares). The final box-and-whiskers plot below emphasizes how urban areas have the highest number of rides.

[PyBer Summary Dataframe](analysis/PyBer_Summary_dataframe.PNG):  
![PyBer_Summary_dataframe](https://user-images.githubusercontent.com/86338416/126919200-6152af12-341d-4fff-8569-f3596dd77fe6.PNG)  

[PyBer Total Fares by City Type](analysis/PyBer_fare_summary.png):  
![PyBer_fare_summary](https://user-images.githubusercontent.com/86338416/126919215-92aafd65-a91e-414a-beda-246c71787a1c.png)  

[PyBer Ride Counts by City Type](analysis/Fig2.png):  
![Fig2](https://user-images.githubusercontent.com/86338416/126919315-5e6dd4f1-0821-4ed7-a106-8254ba7236c2.png)  

## Summary  
Based on the results, it is clear that the ratio of number of drivers to riders is the highest in urban areas and the lowest in rural areas. I would recommend to the PyBer CEO that he or she 1) try to increase the number of riders in rural areas by providing first time user discount codes, incentivizing people to use their service, 2) try to increase the number of drivers in rural and suburban areas by providing bonuses to drivers who give rides in those areas (reallocating some of the current drivers in urban areas to rural and/or suburban areas), and 3) try to hire more drivers who already live in rural areas and will most likely want to stay closer to home, hopefully increasing the number of drivers available in rural areas. These steps will hopefully help balance out fares to be fairly similar regardless of city type, prompting more people in rural areas to use their service.





