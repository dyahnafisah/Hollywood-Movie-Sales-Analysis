# Hollywood-Movie-Sales-Analysis
This project is done in regards to completing SC5010 (Introduction to Data Analysis) course.

## Data Source
The data was extracted from the following link.
> https://www.kaggle.com/datasets/sanjeetsinghnaik/top-1000-highest-grossing-movies

## Objective
The main objective of this project is to analyse how different factors can affect the movie sales especially on the top 1000 highest grossing Hollywood movies.

## Problems
To achieve the desired objective, we define several problems such as the followings.
1. Are the any certain distribution and pattern that the movie sales follow?
2. What are the top distributors and movie titles based on the movie sales?
3. How does the individual factor in the dataset affect the movie sales?
4. How can we build a model to accurately predict the movie sales?
5. What are some recommendations that can be drawn from the results?

## Content
1. Exploratory Data Analysis
2. Model Building
3. Result and Conclusion

## Contributors
1. Dyah Ayu Nurun Nafisah - Exploratory Data Analysis, Predictive Models on Movie Sales
2. Parv Patodia - Predictive Models on Distributors, Genre, License
3. Prabhakaran Nikhita - Clustering using Silhouette Analysis

## Algorithms Used
### Predictive Models on Movie Sales
1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor
4. Neural Network Classifier
### Predictive Models on Distributors, Genre, License
1. XGBoost Regressor
2. Random Forest Regressor
### Clustering
1. Silhouette Analysis

## Results
1. There are some clear patterns found on some variables, especially seasonal pattern on the release date (quarter and month). Summer and winter releases are generally better compared to spring and autumn.
2. Clustering generally shows the separation between the high-valued sales and low-valued sales based on the different variables introduced to the model
3. Predictive models using regression algorithms on the sales did not perform well on the test set for all of the models.
4. Better result was obtained when movie sales was converted into binary variable and predicted using Neural Network.
4. Predictive models on the distributors and license perform relatively well on Random Forest Regressor.

## Conclusion
Despite the limitations of the models, we can roughly predict or suggest how movie sales will perform based on several factors, such as release date, genre, and distributors.

## What did we learn from this project?
1. Data engineering to split the column consists of grouped information
2. Several new algorithms, such as random forest regressor, gradient boosting regressor, Neural Network, XGBoost regressor, and silhouette analysis
3. Extracting the insights from the results and presenting the recommendations obtained from data analysis
