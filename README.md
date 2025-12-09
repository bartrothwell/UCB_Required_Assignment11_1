## Repository: UCB_Required_Assignment11_1
### Assignment: UCB AI/ML Course Required Assignment 11.1
### Author: Bart Rothwell
### Date: 12/9/2025

This README file contains the final report from an investigation into which vehicle attributes affect the sale price of used vehicles.

Link to Jupyter Notebook with the full analysis: https://github.com/bartrothwell/UCB_Required_Assignment11_1/blob/main/RequiredAssignment11_1_Rothwell.ipynb

# Report: Factors Important to Used Car Buyers

### Introduction
This report summarizes the findings of an investigation I performed into which vehicle attributes contribute positively or negatively to the sale price of used vehicles, in order to provide recommendations to used car dealers regarding what consumers value in a used car.
### Method
In order to conduct this investigation, I began with a dataset containing information about the attributes of 426,880 used cars, as well as their sale prices. After selecting only the most relevant data out of this dataset, I used machine learning techniques to develop a model that could predict the sale price from the given attributes. I then used this model to infer which of the vehicle attributes had the greatest effects on the sale price, and whether those effects were positive or negative.
### Limitations
Due to limitations of the data and the modeling process, I wasn't able to make inferences from the model about which vehicle attributes are important for:
- Vehicles that have a high price for a used car (i.e. above $57,000)
- Vehicles that are 20 or more years old
- Vehicles that don't have a clean title

I was also not able to determine:
- Which particular vehicle models are preferred or not preferred by customers (although I was able to determine preferred manufacturers)
- Which geographical regions or states command higher or lower prices for used vehicles
### Results
Subject to the limitations described above, here are my findings regarding the factors that are important to used car buyers:
##### Vehicle Age
By far the most important factor determining how much a buyer will pay for a used car is the age of the vehicle. Obviously, the newer the vehicle, the more the consumer will be willing to pay.
##### Odometer Reading
Like vehicle age, the number of miles on the vehicle has a major impact on what a customer will pay, with customers obviously preferring vehicles with lower odometer readings.
##### Engine Cyclinders
The size of the engine, measured simply as the number of cylinders, is another important factor to consumers, with larger engines being preferred.
##### Vehicle Condition
While the vehicle condition is important to consumers, a surprising result of this study is that the impact of condition on sale price was not as large as that of some of the other vehicle attributes.
##### Manufacturer
The study found that the vehicle manufacturer contributes significantly to what a buyer will be willing to pay.

The 10 most preferred manufacturers, starting from the best, are as follows:
- Lexus
- Toyota
- Audi
- Mercedes-Benz
- Porsche
- Honda
- Rover
- BMW
- Acura
- GMC

The 10 least preferred manufacturers, starting from the worst, are as follows:
- Nissan
- Dodge
- Chrysler
- Ram
- Mercury
- Ford
- Saturn
- Kia
- Pontiac
- Hyundai

##### Fuel Type
The type of fuel used by vehicles is another factor that is important to consumers, with buyers willing to pay more for vehicles that run on diesel than for gas-powered cars. Hybrid and electric cars are valued somewhere in the middle.

##### Type of Vehicle
Certain vehicle types are definitely preferred by customers over others.

Customers are willing to pay more for:
- Trucks, including pickups
- Convertibles
- Off-road vehicles
- Coupes

They will pay less for:
- Sedans
- Mini-Vans
- Hatchbacks
- SUVs
- Wagons

##### Drive Type
The vehicle drive type does contribute to the perceived value of a used car, although less so than the factors above. The study found that consumers are willing to pay more for 4-wheel-drive and rear-wheel-drive vehicles than they are for front-wheel-drive vehicles.

##### Transmission
The transmission type is less of a factor that consumers care about, although there is evidence that buyers pay more for manual transmissions than automatic transmissions, and even more for specialized transmissions that don't fall into either of those categories.

##### Paint Color
The study found that the paint color of vehicles contributes almost nothing to the eventual sale price.

### Recommendations
Based on these results, I recommend that when deciding which vehicles to acquire for sale, dealerships should focus most on obtaining vehicles that:
- Are newer and have been driven fewer miles
- Have larger engines
- Are made by one of the manufacturers on the preferred list above

Other factors to consider would be to favor, in decreasing order of importance:
- Diesel or hybrid/electric vehicles over gas-powered vehicles
- Trucks (including pickups), convertibles, and off-road vehicles over sedans, mini-vans, hatchbacks, and SUVs
- 4-wheel or rear-wheel drive vehicles over front-wheel drive vehicles
- Vehicles in better condition over those in worse condition
- Specialized or manual transmissions over automatic transmissions

Very little emphasis should be put on:
- Paint color
