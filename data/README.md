# Data used for analysis

Our core data is downloaded from [Kaggle](https://www.kaggle.com/pschale/mlb-pitch-data-20152018?select=games.csv&fbclid=IwAR3CxTEd_RQtheRGB_r1ipD03WS0l5pY9M-kLrVKyN_oJRpK3i9FSLCZmLE). Baseball_merged_fin.csv holds this data after we transformed it with codes available in the notebook. We will not upload all the data to github as it exceeds the allowed size limits. Other than that, we have the following csvs: 

- date_n_location.csv - has information on matches and their subsequent locations and dates.
- weather_df.csv - has weather information for given dates of given locations downloaded from [VisualCrossing](https://www.visualcrossing.com/)
- location_weather.csv - is a merged dataframe created from date_n_location.csv and weather_df.csv