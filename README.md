
The goal of this analysis is to identify the key factors influencing check-in volume for business owners on the Yelp platform and provide recommendations to help increase engagement and check-ins.

This analysis is based on a large raw dataset (7.5 GB) of Yelp business data hosted on AWS.

# Raw data
11 tables of Yelp users' info and Yelp business owners' info.
Table names:
"attribute"   "business"    "category"    "checkin"     "elite_years" "friend"      "hours"       "photo"     "review"      "tip"         "user"   

# Package
sqldf;
MatchIt;
dplyr;
ggplot2;
corrgram;
car;
MASS

# Other tools assisted analyzing
Tableau

# Prediction Model
Poisson / Quasi-Poisson Regression
