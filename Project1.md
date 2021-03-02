# Project 1 

## 03/01/2021 

### A description of the housing data you scraped from zillow
I initially had 400 data points, but had to remove some due to incomplete or unusable date. Ultimately, I ended up with 376 data points corresponding to different homes in Austin, Texas. Each data point had information about its price, address, number of beds, number of baths, and its squarefootage. Here are some descriptive statistics about the collected data: 


### A description of your model architecture
Before building the model, I preprocessed the data into a form usable for the model. This included dropping a couple of bad data points as well as dividing all the values for squarefoot by 1000. Next, I created numpy arrays named x1, x2, and x3 that corresponded to each of the 3 features number of beds, squarefootage, and number of baths respectively. I next stacked them together into a variable called xs and made a variable called ys that included all the corresponding prices for the houses. Next, I initialized the model with an input shape of 3. I then compiled the model and fit it on the values in my xs and ys variables. 

At this point, my model had been created, and it was time to start pretictions. I used the same data points that were utilized to train the model to test it, and added the predicitons in another column to the original dataframe. Next, I created one more column called difference that held the value of predicted price minus the true price. 

### An analysis of your model output

### An analysis of the output that assesses and ranks all homes from best to worst deal

