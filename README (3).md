# Airline Price Prediction using ML

This repository contains all the code regarding Airline Price Prediction. It contains the following input variables: </br> </br>

1. Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.</br>
2. Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.</br>
3. Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities.</br>
4. Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.</br>
5. Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.</br>
6. Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.</br>
7. Destination City: City where the flight will land. It is a categorical feature having 6 unique cities.</br>
8. Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.</br>
9. Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.</br>
10. Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.</br>
11. Price: The target variable stores information of the ticket price.</br></br>
 
# Summary -
Among the models considered i.e Linear Regression, GradientBoostRegressor, XGBRegressor, and RandomForestRegressor, the XGBRegressor demonstrated the most promising performance, showcasing a R-squared score of 0.988 and a low Mean Absolute Error (MAE) of 1261.69 on the test dataset.

