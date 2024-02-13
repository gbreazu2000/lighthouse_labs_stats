# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project was to determine if mobile bikes were more likely to be used in regions of Barcelona that was near a highschools. Additionally, I examined different variables that were intentionally pulled from the Yelp and Foursquare API data to determine any potential relationships.

## Process
Step 1 --> My first step was to pull the usable data from both the foursquare and the yelp apis, insert the json data into dataframes and perform data cleaning 
Step 2 --> My second step was joining the bike data and high school data tables through a common key which was the bike station name.
Step 3 --> Then, I explored the relationships using visual plots such as scatter plots and heat maps.
Step 4 -> Then, I created a linear regression model using the columns that had the most relevant relationship to see if it they were statistically relevant.

## Results
I found that it was very difficult to determine a strong relationship between the high school data and the bike station data. There are too many confounding variables that need to be considered.

## Challenges 
The biggest challenge that I faced throughout the project was properly pulling the data from the apis and parsing the data into a clean dataframe as well as finding a key that connected the two sets of data

## Future Goals
If I had more time, I would investigate the bike data over a longer period of time as opposed to a singular timestamp, since it can be very difficult to draw strong conclusions. I would also access more variables from different apis to try and get stronger correlational relationships. 
