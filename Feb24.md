# Informal Reponse 4 

## 02/24/2021 

### Convolve the two 3x3 matrices that were assigned to you with your 9x9 matrix and calculate the resulting two matrices.

![](Matrix2.png)

![](Matrix3.png)

![](Matrix4.png)

 
### What is the purpose of using a 3x3 filter to convolve across a 2D image matrix? 
The purpose of using a 3x3 filter to convolve across a 2D image is to emphasize certain parts of the image such as vertical or horizontal lines so that it can best be used as data in a model. It also makes the image smaller, which is helpful when it is being used in a model. It is essenitally a way of processing the data before it is used. 

### Why would we include more than one filter? How many filters did you assign as part of your architecture when training a model to learn images of numbers from the mnist dataset?
Using more than one filter may allow us to emphaizize multiple features in an image, which might therfore allow for creation of a more effective model. When I built my model on the mnist dataset, I only used one filter, but I may have had better results if I employed multiple. 

### MSE: From your 400+ observations of homes for sale, calculate the MSE for the following.
### The 10 biggest over-predictions
535562223415.2863
### The 10 biggest under-predictions
23479729427135.414
### The 10 most accurate results (use absolute value)
69908328585.21533
### In which percentile do the 10 most accurate predictions reside? Did your model trend towards over or under predicting home values?

The percentiles of the most accurate predicitons definitely vary but they tend to be around the 50th percentile so near the median value. This makes sense because as the values get really large or small, there is less data similar to those houses so the model is less accurate. My model tended to under-predict as shown by the very high MSE for the 10 biggest underpredictions. 

### Which feature appears to be the most significant predictor in the above cases?

The square footage of the homes seems to be the most significant predictor. This does make sense, but I feel that adding an element of location would really improve the model because the price of a house with the same squarefootage can vary drastically based on where it is located. 
