# Assignment 11.1 - What drives the price of a car?

The following report presents the findings of an analysis that explores the pricing of used cars. The analysis identifies the factors that are most important in determining the price of a used car. A large dataset of used car prices along with various factors about the car has been analyzed. The results of this analysis are below.

## Business Undestanding

The used car dealership has hundreds of cars in its inventory and the vehicles need to be priced optimally so that the vehicles sell quickly and the dealer stocks the right vehicles. There are many factors that go into pricing the cars appropriately. Based on historical used car sales, we can develop a model to determine the factors that are most important in pricing a used car and use this model to price the car optimally. 

This can be done by using a supervised learning technique called regression analysis. This technique is suitable for modeling a numerical variable such as the price of the vehicle in this case. The regression model learns from historical data and determines what factors are most important in determining the price of a car. The model also learns how much each of those factors contribute to the price of the car. Once learned, the model is then used to predict the price of a car given a set of key factors about the car.

We will be using a historical data set of used cars to create a regression model that can be used for predicting the price of a used car.





Used car prices increase exponentially as the age of the vehicle decreases, so newer vehicles are priced higher.

The features that heavily impact used car prices are:

- **Year of manufacture** - cars built more recently are priced higher. This is regardless of the odometer readings. In fact, odometer readings do not have much impact on the used car’s price.
- **Condition of the car** - vehicles in excellent and like-new conditions are priced higher. Vehicles that are listed as fair condition are priced lower.
- **Type of the vehicle** - pickups, trucks, and convertible vehicles are priced higher, and sedans, mini-vans, and hatchbacks have a negative effect on prices.
- **Type of fuel** - Diesel vehicles get a higher used car price than gasoline vehicles, and used electric vehicles still carry a premium over gas-powered ones.
- **Size of the vehicle** - full-size and mid-size vehicles command higher prices than compact ones.
- **Color** - paint color does not have much impact on the price, although certain colors such as grey, black, and white fetch higher prices.
- **Title status** - cars with missing title do not have as much value as cars with clean titles.
- **Drive type** - rear-wheel drive and 4-wheel drive vehicles get higher prices than fore-wheel drive vehicles.
- **Transmission type** - manual transmission has a higher impact on prices than automatic transmission ones.

The model can be used to assist in determining the optimal price and inventory levels for used vehicles. Recommendations on pricing used vehicles based on the above findings:

1. Price vehicles based on their age - newer vehicles should be priced higher than older ones.
2. Price vehicles based on their condition - vehicles in excellent and like-new conditions should be priced higher.
3. Price vehicles based on their type - pickups, trucks, and convertible vehicles should be priced higher than sedans, mini-vans, and hatchbacks.
4. Price diesel and electric vehicles higher - gas-powered cars are lower in value than diesel and electric vehicles.
5. Price full-size and mid-size vehicles higher - full-size and mid-size vehicles have higher value than smaller vehicles.
6. Price vehicles based on their title status - cars with clean titles should be priced higher than those with missing titles.
7. Price rear-wheel drive and 4-wheel drive vehicles higher - rear-wheel drive and 4-wheel drive vehicles get higher prices than fore-wheel drive vehicles.
8. Price manual transmission vehicles higher - manual transmission get higher prices than automatic transmission vehicles.

These recommendations can be used to optimize the price as well as inventory levels for used vehicles. The model can also assist in determining the price of a used vehicle based on these factors.
