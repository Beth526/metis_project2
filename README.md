# metis_project2
This project is a webscraping and linear regression project for Metis Project #2. I scraped vinyl record data from Discogs.com for the top 1000 collected records, and data on the artist monthly listeners from Spotify.com. The median sale price on Discogs.com was the target variable, and I used scraped data and feature engineering to predict it. Feature engineering was used to generate new quadratic and interaction variables. Linear regression with lasso and ridge regularization were tested as models using cross-validation, and the final selected model used lasso regularization. The absolute mean error of the final model on the test set was $17.

# Tools used:

-Beautiful Soup

-Selenium

-Scikit-learn

-Seaborn


# Discogs webscraping notebook:
https://github.com/Beth526/metis_project2/blob/master/Discogs_webscraping.ipynb

# Spotify webscraping notebook:
https://github.com/Beth526/metis_project2/blob/master/Spotify_Selenium_Scraping.ipynb

# Final dataframe construction notebook:
https://github.com/Beth526/metis_project2/blob/master/Combining_Discogs_and_Spotify_Data.ipynb

# Feature engineering and model selection notebook:
https://github.com/Beth526/metis_project2/blob/master/Feature%20Engineering%20and%20Model%20Selection.ipynb

# Presentation PDF
https://github.com/Beth526/metis_project2/blob/master/Project2_onl20_ds4_Baumann.pdf

