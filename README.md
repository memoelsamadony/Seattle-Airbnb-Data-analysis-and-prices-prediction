
# Seattle Airbnb Data analysis and prices prediction

This project is part of Data Scientist Nanodegree program that follows the CRISP-DM process
in finding solutions for the questions I aspired to answer from the Data


## About 
This Data set of Airbnb company public data , It  is an American company that operates
 an online marketplace for lodging, primarily homestays for vacation rentals, 
 and tourism activities. Which you can download from [here](https://www.kaggle.com/datasets/airbnb/seattle?resource=download)
 
 Main project files :
 
 - calender.csv : Its the time series data from jan 2016 - jan 2017 , Also conatins if the listing was available or not , the listings id and its price

 - listing.csv : contains data about the properties of each listing , about the neibourhood , about the host and the price

 - reviews.csv : Its the written reviews about the listings , also conatains reviewer id and listing id

 - Seattle Airbnb data analysis and prices predictions.ipynb : The jupiter notebook file where I pose my main three questions : 1-Does the prices vary over the year ? 2- what factors may affect the change in prices ?  3- Can we predict prices to inform hosts and travellers? 

 - Seattle Airbnb data analysis and prices predictions.html : An html that contains the code
 
 - This project include writing a blog post [here](https://medium.com/@memolabib57/data-analysis-for-airbnb-seattle-listings-and-prices-prediction-eb7f7866b99a)

 

## Libraries used
- scikit learn 
- matplotlib.pyplot
- seaborn 
- pandas 
- numpy

These libraries you can install them using pip install or conda 


## Acknowledgements
This [article](https://towardsdatascience.com/when-is-it-ok-to-impute-missing-values-with-a-zero-6d94b3bf1352) really helped me with handling missing values in my data

This [article](https://medium.com/@raj5287/effects-of-multi-collinearity-in-logistic-regression-svm-rf-af6766d91f1b#:~:text=Random%20Forest%20uses%20bootstrap%20sampling,different%20set%20of%20data%20points.)helped me to better understanding to the models I fitted 
