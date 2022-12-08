# airbnb-price-predictor

This repo contains our team's code that analyzes New York City Airbnb listings to understand which features of an Airbnb listing have the greatest impact on its pricing rate.

The original dataset that we analyzed can be found on [Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data).

## Files

The files and their descriptions in this repo are listed below. Files in root directory:
* ***final.pdf*** – final project report with model summaries and figures.

Files in "data/" directory:
* ***airbnb_clean.csv*** - contains the cleaned dataset that we performed our analyses with.
* ***openrefine_history.txt*** - contains exported code from openrefine detailing facets and changes made. Overall results are at the bottom of the document.

Files in "code/" directory :
* ***association.ipynb*** - contains code for association testing (Apriori) for the listing name and rules.
* ***clustering.ipynb*** - contains code for k-means clustering.
* ***correlation_coefficient.ipynb*** - contains code for our Pearson and Spearman correlation scores.
* ***ensemble.ipynb*** – contains code for ensemble classifier models for price tertile prediction.
* ***feature_engineering.ipynb*** - contains code for all of our feature engineering (binning, binarization, etc).
* ***host_listings.ipynb*** - contains code for ANOVA, regression, and classification between price and calculated host listings.

Files in "export/" directory:
* ***association.html*** - exported HTML of association.ipynb.
* ***clustering.html*** - exported HTML of clustering.ipynb.
* ***correlation_coefficient.html*** - exported HTML of correlation_coefficient.ipynb.
* ***ensemble.html*** – exported HTML of ensemble.ipynb.
* ***feature_engineering.html*** - exported HTML of feature_engineering.ipynb.
* ***host_listings.html*** - exported HTMl of host_listings.ipynb.

## Contributors

This project was created by Team Guardians for Comp_Sci 396 Intro to the Data Science Pipeline (Fall 2022) @ [Northwestern University](https://www.mccormick.northwestern.edu/computer-science/academics/courses/descriptions/396-3.html). The following individuals contributed:

* [William Cohen](https://github.com/willcohen2000)
* [Jeffrey He](https://github.com/JeffreyHe101)
* [Bill Wang](https://github.com/silversq)
* [Hugo Zhang](https://github.com/thehugozhang)
