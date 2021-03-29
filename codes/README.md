# Codes used for analysis

Our core data is downloaded from [Kaggle](https://www.kaggle.com/pschale/mlb-pitch-data-20152018?select=games.csv&fbclid=IwAR3CxTEd_RQtheRGB_r1ipD03WS0l5pY9M-kLrVKyN_oJRpK3i9FSLCZmLE). Baseball_merged_fin.csv holds this data after we transformed it with codes available in the notebook. We will not upload all the data to github as it exceeds the allowed size limits. Other than that, we have the following csvs: 

- Term_Proj_Coding_3_Baseball.ipynb - Loads up raw data, and transforms it so that it can be used for meaningful analysis. We also carried out an EDA and further aggregations so that it can be used for analytics
- venue_api.ipynb - This notebook fetches weather data with the use of [VisualCrossing](https://www.visualcrossing.com/) API. The end result of this notebook is a dataframe with locational and weather data for a given day. 
- baseball_regression_analysis.ipynb - we merge the cleaned data and weather data in this notebook and run a series of OLS regressions for exploration.