# ACM Research coding challenge (Fall 2022)

This semester's challenge is especially open-ended. [Here is a dataset](https://www.kaggle.com/datasets/chancev/carsforsale) on Kaggle called "CarsForSale". It contains data scraped from the online car marketplace Cars.com. Each row contains 25 pieces of information about a car's listing, such as its price, year, model, and color.

The challenge is to do *something interesting* with the data. Can you find a pattern, answer a question, or create a visualization? 

# 3 step proccess
# Clean Data
# Find Patterns in Data
# Visualize Useful information


# 1. DATA
Dispay the data types and columns

# 2. PRICE TO INT
Convert Price string to an int for 

# display price


#price to float


data.Price
3. Used/New
Convert all certifications to certified

#display all unique values


#define ToCertified pass in data, replace all with "Certified" with only "Certified"

4. ConsumerRating
Find topmost variables correlated with ConsumerRating
![image](https://user-images.githubusercontent.com/78242653/188547325-470f8086-e07a-4b5a-a4df-da937d98f37e.png)


# from pandas.tools.plotting import scatter_matrix # For older versions of Pandas
from pandas.plotting import scatter_matrix

RESULT
ValueForMoneyRating 0.917873,

ReliabilityRating 0.914597,

ComfortRating 0.860040,

PerformanceRating 0.805849,

have high correlation to consumer rating

5. All CORRELATIONS
Display all correlations

# from pandas.tools.plotting import scatter_matrix # For older versions of Pandas

6. PRICE CORRELATIONS
Display all price correlations

Result
Price has some correlations with Year and anti-correlated to Mileage

data.describe()
7. MAKE
Find most common car sold

8. HISTOGRAMS
Display all availible in histograms

9. VALUE TYPES
Display types

10. HOT ENCODING
Initiate Hot encoding for predictive modeling

#pandas hot encoding


