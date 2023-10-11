# Exploratory Data Analysis - Step by Step

This project was made to learn and improve my Exploratory Data Analysis, following a logic on how to analyze and process data to train a model. 
There's not a "single way" of doing an EDA, but I find this one quite simple and logical to follow and put it in practice. The dataset used is about AirBnB Places in NYC, and I did all the data analysis and treatment from the reading part of the dataset until splitting the data into Train and Test for modeling. 

## 📒 Key Takes

Exploratory Data Analysis is the basis of any Data Scientist. EDA as it's more commonly know, allow Data Scientists to understand their data, work onto cleaning their data, feature engineering knowing what is the problem and the context, and ultimately prepare datasets for training and testing ML Models. 
Starting with a simple study of the shape, info and perhaps some duplicate cleaning is always a good starting point. This way we understand what is Categorical Data in our dataset and what is Numerical Data, so that we can work later on the Features in tandem with the problem and context. I like this order of analysis, but of course there's not a set rule.  

Starting by a Univariate Categorial Analysis like this: 

<img src="https://github.com/4GeeksAcademy/gustavolima-EDA_AIRBNBNYC/blob/main/assets/cat.png" width="500">

And a Univariate Numeric Analysis like this: 

<img src="https://github.com/4GeeksAcademy/gustavolima-EDA_AIRBNBNYC/blob/main/assets/numeric.png" width="500">

We get a better hold of our data, and can immediately draw few conclusions. It's always good practice to note it down on markdown what you see and what you can conclude because it will help understand better the data. 

Upon doing Univariate analysis, next step will be Multivariate Analysis on the Numerical, Categorical and Numerica-Categorial domain as seen here: 

Multivariate Numeric of the Data
<img src="https://github.com/4GeeksAcademy/gustavolima-EDA_AIRBNBNYC/blob/main/assets/multinum.png" width="500">

Multivariate Categorical of the Data
<img src="https://github.com/4GeeksAcademy/gustavolima-EDA_AIRBNBNYC/blob/main/assets/multicat.png" width="500">

Multivariate Numeric-Categorical of the Data
<img src="https://github.com/4GeeksAcademy/gustavolima-EDA_AIRBNBNYC/blob/main/assets/catnum.png" width="500">

This last step, will open even more the data, to understand what correlates to what, so we can withhold a better sense of what the machine might be able to do.  All these graphics and understanding them will allow to properly understand the data but also know where to work the data looking at the context of the problem. The way data is distributed, the statistical information can and will dictate many aspects on how the model will perform. 

Next step of a simple EDA would be to do Feature Engineering, where we clean Outliers (or not) depending on what we are doing, analyze missing data, and finally Standarize / Scale our data so that the Machine can interpret the data and do the needed calculations. 

The last step would be to split the dataset, and in here we can either pick manually what features to maintain or not, or use somehting like a KBest to let the machine through math decide what would be the X amounts you tell of features to be picked up. 



