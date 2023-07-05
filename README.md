# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
to work with website API to retrieve data and proceed to data wrangling and analysis then create a regression model to explain the data
## Process
### (your step 1)
retrieve the data from CityBikes in the city Linz then use the location longitude and latitude to obtain the API from Foursquare, and Yelp API. 
take the data from the retrieved JSON files then work around to make a viable dataframe 
### (your step 2)
make a boxplot, histogram, scatterplot to see the relationship between the number of restaurants and the distance from the station then create a regression model to test the hypothesis 
## Results
the Foursquare API retrieved less information however, broader categories. the Yelp API retrieved more information however, it is limited to restaurant related searches. the final dataframe showed a right skewed histogram between the number of restaurants and the distance from the station. 
the regression model did not show significance with an r^2 of 0.02 and t test p-value 0.550 for name. the data is not significant and shows that the number of bikes availible does not increase with the number of restaurants 
## Challenges 
the timing to complete retrieving the data and constructing the dataframe was very consuming which did not allow room to complete the other parts fully and revise them. 
## Future Goals
i would obtain more data and revise the regression model to have a better fit