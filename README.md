# metis_project2
This project is a webscraping and linear regression project for Metis Project #2. I scraped vinyl record data from Discogs.com for the top 1000 collected records, and data on the artist monthly listeners from Spotify.com. The median sale price on Discogs.com was the target variable, and I used scraped data and feature engineering to predict it. Feature engineering was used to generate new quadratic and interaction variables. Linear Regression with Lasso and Ridge regularization were tested as models using cross-validation, and the final selected model used Lasso regularization. The absolute mean error of the final model on the test set was $17.

Tools used:
-Beautiful Soup
-Selenium
-Scikit-learn
-Seaborn
