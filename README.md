# citibike-pre-post-pandemic-analysis

With data from pre-pandemic (April 2019 to March 2020) and data from post-pandemic (April 2022 to March 2023) from the CitiBike project, clean and export data for visualization in Tableau. Look at trends and changes in bike station popularity and ridership changes.

Data was collected from: https://citibikenyc.com/system-data

Data was cleaned in jupyter notebook 'citi-bike-pre-post-pandemic.ipynb' and information was exported as csv files to be used in Tableau Visualizations.
    * pre-pandemic raw data from months April 2019 to March 2020 was saved in the 'pre/raw' folder
    * post-pandemic raw data from months April 2022 to March 2023 was saved in the 'post/raw' folder
    * exported data for pre-pandemic was saved in the 'pre/output' folder
    * exported data for post-pandemic was saved in the 'post/output' folder

For Tableau Visualizaitons the workbook 'Station Trends Pre-Pandemic and Post-Pandemic.twbx' was used and visualizations were uploaded to Tableau Public here:
    https://public.tableau.com/app/profile/kathleen.anderson7696/viz/StationTrendsPre-PandemicandPost-Pandemic/Station
    * the data used for the Tableau visualizations were mainly
    ** concat_pre_df.csv found in the 'pre/output' folder
    ** concat_post_df.csv found in the 'post/output' folder
