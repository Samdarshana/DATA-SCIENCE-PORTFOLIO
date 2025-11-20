                                                              NYC TAXI EDA

This project performs exploratory data analysis (EDA) on the NYC Taxi dataset to explore patterns in trip duration, distance, time-of-day effects, traffic indicators, and pricing behavior. The analysis includes data cleaning, aggregations, visualizations, and key insights.

The full NYC Taxi dataset is large and cannot be uploaded to GitHub.

**Download the dataset here**: https://drive.google.com/file/d/1IWK7v7FL3Zg9AIh6PvG7b2rqri7rFKil/view?usp=drive_link

***How to Run the Project***
1. Download the dataset from Google Drive and place it inside:
   `1-EDA/1-NYC-TAXI-EDA/data/`

2. Install required libraries:
   pip install pandas numpy matplotlib seaborn

3. Open the Jupyter notebook:
   `EDA_Assg_NYC_Taxi_Samdarshana_Gururajan.ipynb`

4. Run all cells to reproduce the analysis.

Key Insights
- Clear peak in taxi demand during early mornings (8–9 AM) and evenings (6–8 PM), indicating strong commuter travel patterns.
- Trip distance shows a strong positive relationship with fare amount—longer trips naturally lead to higher fares.
- Majority of trips are short-distance city rides, while a smaller number of long trips contribute heavily to total revenue.
- Certain pickup zones consistently show high activity, suggesting these are major transit, business, or tourist hubs.
- Seasonal and time-of-day factors heavily influence trip volume, with weekends showing more late-night activity.
- Data cleaning revealed missing or inconsistent values in fare, distance, and passenger count fields, requiring preprocessing before analysis.


