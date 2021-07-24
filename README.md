## Car-Price-Prediction
## 16th rank solution

Mathcompany.com

# About Data

With the rise in the variety of cars with differentiated capabilities and features such as model, production year, category, brand, fuel type, engine volume, mileage, cylinders, colour, airbags and many more, we are bringing a car price prediction challenge for all. We all aspire to own a car within budget with the best features available. To solve the price problem we have created a dataset of 19237 for the training dataset and 8245 for the test dataset.

# Dataset Description
Train.csv - 19237 rows x 18 columns (Includes Price Columns as Target)

Attributes:
- ID
- Price: price of the care(Target Column)
- Levy
- Manufacturer
- Model
- Prod. year
- Category
- Leather interior
- Fuel type
- Engine volume
- Mileage
- Cylinders
- Gear box type
- Drive wheels
- Doors
- Wheel
- Color
- Airbags
Test.csv - 8245 rows x 17 columns
    
# Skills:
Multivariate Regression
Big dataset, underfitting vs overfitting
Optimizing RMSLE to generalize well on unseen data
    
# Evaluation

What is the Metric In this competition? How is the Leaderboard Calculated ?
The submission will be evaluated using the RMSLE metric. One can use np.sqrt(mean_squared_log_error(actual, predicted)) to calculate the same
This hackathon supports private and public leaderboards
The public leaderboard is evaluated on 70% of Test data
The private leaderboard will be made available at the end of the hackathon which will be evaluated on 100% of Test data
The Final Score represents the score achieved based on the Best Score on the public leaderboard
