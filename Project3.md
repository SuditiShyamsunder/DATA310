# Project 3
## 04/16/2021
### Using two machine learning methods predict population values at 100 x 100 meter resolution throughout your selected country. Validate the two models using different methods presented in this class. Write a report assessing the two approaches and which of the two models was more accurate. Be sure to account for spatial variation throughout your selected location and provide substantive explanations for why those variations occurred. 

For this project, I used data from worldpop to create a linear regression and random forest model to predict populaiton counts throughout the country. First, many packages were installed and imported such as raster, tidymodels, and sf. Next, I brought in the data and created a raster stack and did some cleaning of the data. Then the data was split and some was reserved for testing and the rest was reserved for training the linear regression model. Once the recipe and workflow were set up, the raster stack was converted to a dataframe, and the prediction step occured, and then it was convefrted back to raster form where more calculations occurred. The process is very similar for the random forest model. 

The measure that I used to determine the relative accuracy of the models was diff_sums, which is the difference between the predicted population sum and the actual population sum. The variable population_sums contains the predicted value, and the variable cri_pop15 contains the actual value. If you look at the min and max values for the linear regression and random forest models, you can see that in both cases the diff_sums values tend to be negative. This means that the actual values must be larger than the predicted values, which means that both models tend to underpredict. 

![](white1.png)

The plot above shows population distribution based on predicted values. You can see that there is a high predicted population concentration at the center of the country. This is shown by the green region in the center, and the color faded to pink and then white as the distance gets closer to the coast. 

![](green1.png)

![](green3.png)





![](white2.png)

![](green2.png)
