<<<<<<< HEAD
# Study Group A9: R Group project

Group Members: Arman Topchu, Kaize Ying, Leonie Bick, Lorenz Freigassner, Tafadzwa Chinanzvavana, Yiyue Hu, Vrinda Gupta

# Copenhagen AirBnB prices

## Executive summary

Based on the analysis of the data set we conclude that the best predictors of AirBnB prices for a 4 night stay for 2 people in Copenhagen are;

1.  Type of property – *the bigger and more private the property is the higher the price*
2.  Number of reviews and review scores – *this is used as a proxy for the quality of the property as the higher the number of review and ratings the better the quality of the property*
3.  Number of people the property accommodates – *properties that accommodate more people tend to have higher prices*
4.  Neighborhood the property is located – *more exclusive/ suburbs with properties located near the city have higher prices compared to others*
5.  Availability of the property in the next 30 days – *properties available within the next 30 days tend to cost more as it is assumed the person is willing to pay more as the trip was likely booked without planning whereas more than 30 days the person is usually flexible and will likely look for bargains before booking*
6.  Reviews per month

To conduct our analysis and come up with model that best predicts the price we analysed the data set, and selected variables that drive prices from a logical point of view and used those for our base model. From this base model we conducted statistical analysis of all the other variable looking at the correlations to prices and added variables that were correlated with prices and improved on our models. Although more variables that the 6 variables included above were correlated to prices most of them did not significantly affect the price most likely due to their own correlation to variables already in the model thus we omitted them.

In conclusion, the model that best predicts prices is  **log(price_4\_nights) = prop_type_simplified + number_of_reviews+ review_scores_rating + room_type + accommodates + neighbourhood_cleansed_simplified+ availability_30+ reviews_per_month** and it explains 52.6% of the variation in prices of Airbnb rentals for a 4 night stay for 2 people in Copenhagen

=======
# Study Group 9
>>>>>>> 80fe09dc121869e5710bed1d34bfa9bbfd0c8b04

