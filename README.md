# Udacity-Create-A-Data-Science-Blog-Post
A basic analysis of the Boston Airbnb listings dataset to find various pricing trends.

## Synopsis
This notebook aims to find out various trends in pricing that can be seen in the different Airbnb listings in Boston, and tries to answer the following questions:
1. How do prices vary across the different regions in Boston?
2. How does pricing scale across different types of properties in Boston?
3. What are the most and least common amenities in Boston?
4. Can we create a simple model to attempt to predict prices in Boston, using simply neighbourhood and property data?

The results of this analysis have been summarized in this article: https://medium.com/@unstablereaper/airbnbs-in-boston-an-analysis-of-the-region-and-pricing-9d56696ea0b

## Packages used:
The project was run on an Anaconda distribution of Python 3.6. The following libraries were used:
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
5. Scikit-Learn
6. os (inbuilt library)

## Summary of Results
From our Analysis we have understood the following:
1. Downtown seems to have the absolute cheapest properties, but Roslindale, Allston and Hyde Park are the cheapest neighborhoods to rent from. Ignoring outliers, Bay Village seems to be the most premium region.
2. Apartments are by far the most common type of listings, with houses a distant second. Surprisingly apartments are much more expensive than houses. 
3. Wi-Fi, heating and smoke detectors lead the way, with 98%, 96% and 92% respectively. Kitchens are also very common, with 88% of properties containing them. However, care must be taken to note that very few properties are explicitly stated as wheelchair accessible, at around 1.3%.
4. We were unable to create a model that succesfully predicts pricing. Further analysis is needed

## Acknowledgements and Sources:
I was able to obtain the relevant data from here:
https://www.kaggle.com/airbnb/boston?select=listings.csv

I would like to thank Udacity for the opportunity to complete this project.
