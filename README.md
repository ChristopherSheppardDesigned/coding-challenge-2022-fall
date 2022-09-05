# ACM Research coding challenge (Fall 2022)

This semester's challenge is especially open-ended. [Here is a dataset](https://www.kaggle.com/datasets/chancev/carsforsale) on Kaggle called "CarsForSale". It contains data scraped from the online car marketplace Cars.com. Each row contains 25 pieces of information about a car's listing, such as its price, year, model, and color.

The challenge is to do *something interesting* with the data. Can you find a pattern, answer a question, or create a visualization? In case nothing comes to mind, here are some ideas, with varying complexity:

- What qualities about a car do buyers seem to value the most?
- Make a graph to visualize the most popular car models over time.
- What colors of cars are most expensive?
- Do different brands try to appeal to people looking for different things?
- Come up with your own algorithm to figure out how good of a deal a listing is and compare it to the one in the dataset (`DealType`).
- Use [cluster analysis](https://en.wikipedia.org/wiki/Cluster_analysis) to group the cars into categories.
- How do people's taste in cars differ between states?
- Train a machine learning model to predict some aspect of a car based on other information from its listing.

However, we strongly encourage you to come up with your own problem to solve!

You can use any programming language, framework, or library you want, but we recommend [creating a notebook in Kaggle](https://www.kaggle.com/docs/notebooks) and using Python. This will run in your browser, interlaces code with documentation, allows you to import the CarsForSale dataset easily by pressing the "Add data" button, and gives you access to Python's high-quality, high-level libraries for working with data. [Learn more about data science in Python.](https://www.w3schools.com/datascience/ds_python.asp)


# 1. DATA
dispay data
# 2. PRICE TO INT
Convert string to int

# display price


#price to float


data.Price
3. Used/New
Convert all certifications to certified

#display all unique values


#define ToCertified pass in data, replace all with "Certified" with only "Certified"

4. ConsumerRating
Find topmost variables correlated with ConsumerRating


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


