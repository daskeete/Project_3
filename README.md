# Project_3

Selected Country: Cameroon

I chose to work with Cameroon because it's the same country that i used in project 2 where we used demographic and housing data to predict wealth outcomes. 
Cameroon is a relatively large country in Central Africa and it is home to approximately 25.88 million people. Below is a population density map of Cameroon and it shows that most of the population is situated in the northern half of the country. Interestingly not a lot of people like to live on the coast. About 20% of the land is used for agriculture and 41% of the land is covered by forests. Most of this forest land is located in the southern part of the country which explains why the population is concentrated in the northern half of the country.



![pop_map](pop_map.jpeg)


Below is a map of Cameroon and it's primary administrative regions.

![primary](primary.png)

I also decided to focus on the region Adamaoua since my computer didn't want to hand over any extra RAM.
Below is a plot of the region as well as its subdivisions.

![adamaoua](adamaoua.png)

Using two machine learning methods predict population values at 100 x 100 meter resolution throughout your selected country

## Linear Regression

Plot showing predicted population sums

![popsums](popsums.png)


Plot showing difference between real population sums and the predicted values.
From this graph we can see that the model tends to overpredict population values for city areas.
For easy interpretation < 0 is an overprediction (yellow areas on the map) and > 0 is an underprediction.

![diffsums](diffsums.png)


Below is a 3D plot of the difference between real population sums and the predicted values. Anywhere you see a hole on this plot is where the model overpredicted. 
There are virtually zero mountains on this plot so the model rarely ever tended to underpredict.

![3d](LR_3d.PNG)


Validate the two models using different methods presented in this class


Write a report assessing the two approaches and which of the two models was more accurate


Be sure to account for spatial variation throughout your selected location and provide substantive explanations for why those variations occurred
