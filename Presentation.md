# Final Project Presentation 

## 05/10/2021 

### Abstract 

Fetal mortality is a serious concern in countries throughout the world. In the United States, 1 in 160 deliveries still results in stillbirth. In 2019, the global neonatal mortality rate was 19 deaths per 10000 live births. In 2015, about 2.7 million children died in their first month of life. Location also plays a key role in these trends, and neonatal mortality is highest in central and southern Asia as well as in sub-Saharan Africa. In these areas, the rate is 29 deaths per 1,000 live births. It is a goal of nations and health care providers globally to reduce fetal mortality rates and increase fetal health as a whole. In fact, Unicef lists one of their Sustainable Development Goals (SDGs) as aiming to end/reduce preventable deaths of newborns and children under 5 years of age within the next decade. In order to take that step, it is crucial to be able to measure and predict the health of a fetus. One way to measure fetal health is by using a machine known as a Cardiotocogram (CTG). These are not too complex and are a cheap and accessible way to measure fetal health. CTGs function by sending ultrasound pulses and reading the responses. This allows for the collection of fetal heart rate (FHR), fetal movements, uterine contractions, etc. Through this project, I am aiming to discover if a machine learning model can be used to predict fetal health based on these measurements from a CTG. This leads to my central research question: How well can machine learning models be used to predict fetal health based specifically on measurements from cardiotocograms? In this project, I used a dataset from Kaggle that had 2126 records of measurements from Cardiotocograms. After these measurements were collected through CTGs, they were then classified by OBGYNS into 3 categories: Normal, Suspect, and Pathological. The dataset includes 21 features that are all continuous variables. The 22nd column, the target column, is called 'fetal_health' and includes a classification of 1, 2, or 3 corresponding to Normal, Suspect, and Pathological respectively. Here is a detailed summary of the dataset. The most successful model that I built was a Logistic Regression Classification Model with Keras. The neural network that I built consisted of an input layer, hidden layers, and then an output layer. The input layer is where the measurements and observations are fed to the model, the hidden layers are wehrer the neural network makes connections between the data and learns about the data, and the output layer is where the final output is discovered. The accuracy of my model was about 87% on the training dataset and 76% on the testing dataset. This is honestly much higher than I was expecting considering the length of this project, but I was pleasantly surprised! I think that this may have been due to the extremely clean dataset that I was able to find that made it easier to create a pretty solid model. It seems that 95% is the general threshold to achieve in order for a model to be considered successful in research such as this that deals with medical data. 

### Presentation: 
[Video of Presentation](https://youtu.be/kvMwvao4sRM)


#### Works Cited 
https://www.pluralsight.com/guides/classification-keras

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6822315/

https://link.springer.com/chapter/10.1007/978-3-319-07773-4_19
