# End-To-End-Real-Estate-Price-Prediction-Model
Real Estate Price Prediction is the process of estimating or forecasting the future prices of real estate properties, such as houses, apartments, or commercial buildings. The goal is to provide accurate property rates to buyers, sellers, investors, and real estate professionals to make informed decisions about real estate transactions. For the task of Real Estate Price Prediction, we need historical data with various features that can influence property prices. The dataset used here is Real Estate data from [Statso](https://statso.io/real-estate-prediction-case-study/).
The dataset contains 7 columns: Transaction date, House age, Distance to the nearest station(m), Number of convenience stores, Latitude, Longitude and House price of unit area. We will find the relation between the first six parameters and house price and then conclude that what exactly is more crucial in predicting the house price of unit area.

The process we will follow:
1) Gather relevant data from various sources, including real estate databases, government records, online listings, and other public or private sources.
2) Clean and prepare the collected data by handling missing values, removing outliers, and converting categorical variables into numerical representations.
3) Create new features or transform existing ones to capture important information that can influence real estate prices.
4) Explore and visualize the data to gain insights into its distribution, correlations, and patterns.
5) Choose appropriate machine learning algorithms or predictive models for the task.
6) Train the selected model on the training data, optimizing its parameters to make accurate predictions.
7) Implement the same on Dash Application.

Here we have used [Linear Regression Model](https://en.wikipedia.org/wiki/Linear_regression) to predict the house prices. Linear Regression Algorithm is a statistical technique for calculating the value of a dependent variable based on the value of an independent variable. The goal of linear regression is to find the best-fit line that describes the relationship between the dependent and the independent variable.

Upon implementing the same, we had following output:
1) House Age: This shows a very weak negative correlation with house price, implying that age is not a strong predictor of price in this dataset.
2) Distance to Nearest Station: Has a strong negative correlation with house price. It indicates that properties closer to stations tend to have higher prices, which is a significant factor in property valuation.
3) Number of Convenience Stores: Displays a moderate positive correlation with house price. More convenience stores in the vicinity seem to positively affect property prices.
4) Latitude and Longitude: Both show a weak correlation with house prices. Latitude has a slight positive correlation, while longitude has a slight negative correlation .

