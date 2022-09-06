# ACM Research coding challenge (Fall 2022) 
# CHRISTOPHER SHEPPARD

This semester's challenge is especially open-ended. [Here is a dataset](https://www.kaggle.com/datasets/chancev/carsforsale) on Kaggle called "CarsForSale". It contains data scraped from the online car marketplace Cars.com. Each row contains 25 pieces of information about a car's listing, such as its price, year, model, and color.

The challenge is to do *something interesting* with the data. Can you find a pattern, answer a question, or create a visualization? 

# 3 step proccess
# 1. Clean Data
# 2. Find Patterns in Data
# 3. Visualize Useful information

# 1.1 DATA
Dispay the data types and columns

# 1.2 PRICE TO INT
Convert Price string to an int for future processing

![image](https://user-images.githubusercontent.com/78242653/188547854-fc72e862-63e8-43fd-850c-061c0116448e.png)

RESULT: Price is now a float 64

![image](https://user-images.githubusercontent.com/78242653/188547887-2c3a11d8-ca0e-43b8-9949-39de477a36fb.png)

# 1.3 Used/New
Convert all certifications to certified

![image](https://user-images.githubusercontent.com/78242653/188548022-5d63af0f-59a3-45dc-87a1-b589d191b38b.png)

RESULT: Now only Used and Certified are the only unique values

![image](https://user-images.githubusercontent.com/78242653/188548052-399bd9f8-7cb7-494e-8479-c5cf4aae6b17.png)

# 2.1 ConsumerRating
Find topmost variables correlated with ConsumerRating
RESULT: CustomerRating Mean is 4.702762961382547

![image](https://user-images.githubusercontent.com/78242653/188548328-e758a8f5-fe9f-468a-acf8-89fdcfa2aba4.png)

![image](https://user-images.githubusercontent.com/78242653/188547325-470f8086-e07a-4b5a-a4df-da937d98f37e.png)

RESULT: These 4 columns have a high correlation to consumer rating
ValueForMoneyRating 0.917873,

ReliabilityRating 0.914597,

ComfortRating 0.860040,

PerformanceRating 0.805849,


# 2.2 All CORRELATIONS
Display all correlations

![image](https://user-images.githubusercontent.com/78242653/188548714-6ebc3660-5b1a-4e40-9891-ae44d0209e09.png)

![image](https://user-images.githubusercontent.com/78242653/188548927-425bb134-63dc-4e7e-b8f9-f715b2bb8cea.png)


# 2.3 PRICE CORRELATIONS
Display all price correlations

![image](https://user-images.githubusercontent.com/78242653/188548770-8466e5ba-265e-4bcc-9a2b-afb798356f02.png)

RESULT: Price has some correlations with Year and an anti-correlated to Mileage

# 2.4 MAKE
Find most common car sold

![image](https://user-images.githubusercontent.com/78242653/188549279-e3347362-c961-49ed-9343-9b0296aacfe0.png)

# 3.1 HISTOGRAMS
Display all availible in histograms

![image](https://user-images.githubusercontent.com/78242653/188549220-8ef1df5b-cb86-4522-9d35-5d46d23fe8e8.png)

# 3.2 VALUE TYPES
Display final data types

![image](https://user-images.githubusercontent.com/78242653/188549528-9e9f3010-895c-4605-9b25-f7bdd463d2eb.png)

# 3.3 HOT ENCODING
Initiate Pandas Hot encoding for future predictive modeling

![image](https://user-images.githubusercontent.com/78242653/188549487-d7dd792b-6d18-4eb0-8f3d-b7a240ee69a5.png)



