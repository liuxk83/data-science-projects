# Data Science Projects
*Kevin Liu*

This repo contains some data science projects I've worked on in the past. Each project is stored in its own directory, which contains a Jupyter Notebook (.ipynb) or R Markdown (.Rmd) file, as well any additional relevant non-data files (such as a presentation). Relevant data files are stored in [this Google Drive folder](https://drive.google.com/drive/folders/1xRFNW1otsL3ipbrzfWAr8oMpZuVcL779?usp=sharing). The projects include:

* [Airbnb Ratings Analysis: Evaluating Factors of Rental Listing Quality](/airbnb-ratings-analysis): Uses regression analysis to investigate key variables that may contribute to the quality of an Airbnb listing.
  * We use two dependent variables - overall score and location score - to represent listing quality, and we consider the following kinds of predictors:
    * Intrinsic (i.e. listing-specific) variables: Price, amenities, etc.
    * Sentiment of listing reviews: Polarity and subjectivity
    * Extrinsic variables (from external datasets): Regional crime rate, home value, and hotel value
  * This was a group project that I worked on, alongside Rohit Jagga. All datasets are public and available online.
  * Technologies/libraries used: Pandas (data processing), statsmodels (regression), and NLTK (sentiment analysis).
* [Instacart Market Basket Analysis](/instacart-market-basket-analysis): Explores Instacart user purchase behavior and uses customer lifetime value (CLV) and clustering models to characterize this behavior.
  * We focus on understanding questions like when customers tend to place orders, what kinds of products they tend to buy (as well as what their favorites are), and how this behavior contributes to a customer's value to Instacart.
  * This was a group project that I worked on, alongside Paul Heysch and Madeleine Song. All datasets are public and available online - they were originally released by Instacart as part of a [Kaggle competition](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data).
  * Technologies/libraries used: Pandas (data processing), Apache Spark (big data processing), scikit-learn (PCA, clustering, etc.), and lifetimes (CLV modeling).
* [Song Popularity Analysis](/song-popularity-analysis): Investigates the effects of lyrical and non-lyrical features on song popularity by testing various machine learning models (linear regression, logistic regression, random forest, and neural network).
  * We use two measures of "song popularity" as our dependent variables - a chart-based binary variable and a continuous variable based on frequency/recency of plays. We use linear regression to model the latter and the other three models (logistic regression, random forest, and neural network) to model the former.
  * This was a group project that I worked on, alongside Jurti Telushi. All data originated from the MusicODataset, a publicly available song dataset that was itself based on Spotify and Billboard data, which can be found [here](https://marianaossilva.github.io/DSW2019/).
  * Technologies/libraries used: Text analysis, glmnet (linear/logistic regression), and keras (deep learning).

If you are interested in learning more about any of these projects, feel free to reach out at liuxk83@gmail.com.
