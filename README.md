# Videogames Analysis  
## Description:  
Historical data on game sales, user and expert ratings, genres and platforms (for example, Xbox or PlayStation) are available from open sources. 
We need to identify the patterns that determine the success of the game. This will allow you to place a bet on a potentially popular product and plan advertising campaigns. 
Data provided up to 2016. Let's imagine that it is now December 2016, and a campaign is planned for 2017. It is necessary to work out the principle of working with data. 
It doesn't matter whether you forecast sales for 2017 based on 2016 data or 2027 sales based on 2026 data. 

![image](https://github.com/gulshart/Games-Analysis/assets/146486882/c5ea2ec8-6191-4e8e-9313-55b9b5b06dc5)


![image](https://github.com/gulshart/Games-Analysis/assets/146486882/593cb181-45bd-4479-bc45-04401bfae5ae)


## Conclusion:
Gaming platforms were analyzed. The source data contains information on 9,701 games and 20 different platforms from 1980 to 2016, providing year of publication, genre, sales by region, user and critic ratings, and age rating. 
During data preprocessing, the column names were converted to lower case, in the column with the year of issue the data was converted to numeric format, and duplicates were checked. 
The omissions, of which there were a small number, were removed. About 40% of gaps were found in the ratings columns; they were left replaced with a placeholder for the age rating, since if they were removed, 
information about genres, sales, etc. would be lost. Global sales have been calculated in the 'total_sales' column.

The study revealed that games before 2000 can be neglected due to the small number, and the platforms that emerged around 2000 had already disappeared by 2008, so the current period was taken as 2013-2016.
The top selling platforms for the period from 1995 to 2016 are the platforms PS2', 'X360', 'PS3', 'Wii', 'DS', 'PS', 'PS4', 'GBA', 'PSP', '3DS'. The PS2 peaked in 2004 and saw its profits decline until 2011.
The Wii saw a sharp jump in 2009 and a sharp drop in sales. Of the new platforms, the PS4 is the most successful - it has the highest sales over the past 3 years.
