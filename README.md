# Space_titanic

This data set is taken from the kaggle space titanic data set link: https://www.kaggle.com/competitions/spaceship-titanic/overview

In essence, this project is completed. However it is not yet optimized due to the fact that model accuracy can still be improved with different feature engineering techniques, parameter tuning and the different choice of the machine learning algorithms.

Applied machine learning models to predict passenger disappearance.

In this project, my task is to predict whether a passenger was transported to an alternate dimension during the Spaceship Titanic's collision with the spacetime anomaly. To with the prediction, a set of personal records recovered from the ship's damaged computer system is given.

File and Data Field Descriptions:

*train.csv - Personal records for about two-thirds (~8700) of the passengers, to be used as training data.

*test.csv - Personal records for the remaining one-third (~4300) of the passengers, to be used as test data. Your task is to predict the value of Transported for the passengers in this set.

* `PassengerId` - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.
 
* `HomePlanet` - The planet the passenger departed from, typically their planet of permanent residence.
CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.

* `Cabin` - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.

* `Destination` - The planet the passenger will be debarking to.

* `Age` - The age of the passenger.

* `VIP` - Whether the passenger has paid for special VIP service during the voyage.

* `RoomService, FoodCourt, ShoppingMall, Spa, VRDeck` - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.

* `Name` - The first and last names of the passenger.

* `Transported` - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.



