# SOLAR RADIATION PREDICTION
Data Source:Kaggle

ABOUT THE DATASET

The dataset consists of meteorological data from the HI SEAS weather station during 4 months.As the world increasingly shifts towards renewable energy sources, accurate solar radiation prediction becomes crucial for optimizing solar power generation, improving energy storage systems, and enhancing grid stability.

FEATURES

UNIXTime

Date and time representation widely used in computing

Data

Date during the data collection

Time

time during radiation in 24hr format

Radiation

Solar radiation in w/m^2

Temperature

atmospheric temperature in farenheit

Pressure

atmospheric pressure in Hg

Humidity

atmospheric humidity in %

WindDirection

winddirection in degrees

speed

wind speed in miles per hour

TimeSunRise

sunrise time in hh:mm:ss

TimeSunSet

sunset time in hh:mm:ss

Here’s a brief overview of the steps involved in this project:
-Data Loading: Imported the dataset into a Data Frame to start the analysis.
-Data Exploration: An initial exploration of the dataset was conducted to understand the distribution, trends, and relationships between different variables.
-Data Cleaning: This step involved handling missing values, correcting errors, and ensuring the data was clean and ready for analysis.
-Encoding: Categorical variables were encoded using datetime functions and regular expressions to convert them into a numerical format suitable for machine learning models.
-Feature Selection: Relevant features were selected based on their importance and correlation with the target variable to improve model performance.
-Outliers Removal: Outliers were identified and removed to ensure they did not negatively impact the model's performance.
-Model Creation: Several models, including Linear Regression, Decision Tree, Random Forest, and Support Vector Regression (SVR), were created and evaluated. The Random Forest model achieved the highest accuracy of 94%.
-Hyperparameter Tuning: Using RandomizedSearchCV, the hyperparameters of the Random Forest model were tuned to further enhance its performance.
-Streamlit App Development: A user-friendly interface was designed using Streamlit to allow users to input data and receive solar radiation predictions.
