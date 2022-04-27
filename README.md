# Phase_2_Project
# Phase 2 Project: Seattle Real Estate
## By: Rachel Eastman
Background: For this project, I am working for a real estate agency that helps clients buy homes. I will provide advice to buyers about how to buy the least expensive houses within their price ranges. Using descriptive and inferential statistics along with multiple linear regression modeling, I was able to select variables that would be important to consider when trying to buy the least expensive houses.

## The Data:
The data I used for this project was:
[kc_house_data](https://github.com/rcasey106/Phase_2_Project/blob/main/kc_house_data.csv)

## Methodology & Results:
Using descriptive and inferential statistics along with multiple linear regression modeling, I was able to select variables that would be important to consider when trying to increase the selling price of a house. First, I used descriptive statistics to find the averages of each variable. The variables I used are square feet of living, latitude, longitude, and condition.
Then, I checked for multilinearity and found the correlations between price and these X variables and concluded they had linear relationships.
I used a linear regression model to view the exact relationship between price and these variables. Finally, I verified the assumptions of the model.

![alt text](https://github.com/rcasey106/Phase_2_Project/blob/main/condition2.png)
![alt text](https://github.com/rcasey106/Phase_2_Project/blob/main/waterfront_final.png)
![alt text](https://github.com/rcasey106/Phase_2_Project/blob/main/lat.png)
![alt_text](https://github.com/rcasey106/Phase_2_Project/blob/main/long.png)
![alt_text](https://github.com/rcasey106/Phase_2_Project/blob/main/sqftliving2.png)

## Discussion and Conclusion
My final model suggests:
•	Square feet of living is important, with each square foot increasing the selling price of the house by $277. 

•	The latitude and longitude are important, meaning the location of the house makes a difference in buying price. Location, location, location!

•	Having a waterfront property increases the price of the house by over $1.1 million.

•	Each increased “condition” level of the house increases the house value by ~$40,000.

These are important factors to consider when buying a house. If a client is looking for a budget friendly house, choosing fewer square feet, considering the location, and overall condition of the house are important, which is what I expected my model to show.

## Final Recommendations:
•	1. Location is important. Waterfront houses, latitude around 47, and longitude of -122 tend to have the highest selling price. To avoid higher priced houses, avoid houses in these areas.

•	2.  A house in “very good” condition will increase selling price the most. Recommend buying a house in a lower condition level to decrease the price of the house.

•	3.  Square feet of living is also important. The more square feet, the higher the selling price.  Find a house with the appropriate amount of square feet for your budget,

