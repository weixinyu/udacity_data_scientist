#Documentation
-------------
## Motivation for the project
Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Seattle, WA. This project is to investigate on the data of airbnb and answer the following business questions:
1. What are the prices of those with different room type?
2. What are the review scores of those with more availability?
3. How well can we predict the price?

##  Libraries:
* numpy - The fundamental package for scientific computing with Python
* pandas - Pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, and most of the data analysis in this project is based on the dataframe in Pandas.
* matplotlib - This is package used for generating statistics plot
* sklearn - This is a simple and efficient tools for predictive data analysis, and the linear regression model in this package is used in this project
* seaborn - This is a powerful Python data visualization library based on matplotlib. It provides high level interface for drawing statistical graphics.


## Project Repository files:
* Airbnb_Data_Exploration.ipynb - Code with appropriate comments, analysis, and documentation.
* README.md - Documentation

## Result Summary:
*  The price of Entire home is higher than that of Private room, and the price of Private room is higher than that of Shared room.
*  The review scores of low availability is a bit higher, but the difference is quite narrow.
*  The best linear regression model achieves a r2 score of 0.56. Among the coefficients of the best model, the room type matters most. The shared room has the biggest negative correlation with the price. The private room has the second biggest negative correlation with the price.

## Acknowledgements
In this project, I have benifited the knowledge from Udacity program Data Scientist and worked based on some demo codes from Putting It All Together - Solution.ipynb.

