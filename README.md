# Cricket-Dashboard-and-Reporting

## Brief of the project
This dashboard helps in identifying the performances of cricket players based on the statistics extracted from the ESPN website. The data was extracted as JSON file using a web crawler. JSON file was then converted to csv file using Python.

## Requirements to analyze from the dataset:
### Openers
- Batting Average must exceed 30.
- Strike Rate should be over 140.
- The player must have batted in more than 3 innings.
- At least 50% of the player's runs should come from boundaries.
- The batter should have a batting position of less than 4.
### Middle ordered batsmen
- Batting Average must be greater than 40.
- Strike Rate should exceed 125.
- The player must have batted in over 3 innings.
- The average number of balls faced by the batter per innings should be more than 20.
- The batting position must be higher than 2.
### All rounders
- Batting Average must be over 15.
- Strike Rate should be more than 140.
- Players must have batted in at least 2 innings.
- Batting Position should be greater than 4.
- Players must have bowled in more than 2 innings.
- Bowling Economy must be less than 7.
- Bowling Strike Rate needs to be under 20 balls per wicket.
### Bowlers
- Bowled in more than 4 innings.
- Bowling Economy is less than 7 runs per over.
- Bowling Strike Rate is under 16 balls per wicket.
- Bowling Style must be "Fast".
- Bowling Average should be less than 20 runs per wicket.
- Dot Ball percentage must exceed 40%.

## Steps:
1. Utilized bright data to scrape the required information from sports website such as ESPN.
2. Using the JSON file extracted as the output from previous step, we go through a series of steps to cleanse the data and transform it to a CSV file.
3. Data transformation is done using the JSON module in the transform_json.ipynb file.
4. JSON files are iterated over loops to extract data and finally convert them to csv files.
5. The CSV file is now uploaded to a Pandas dataframe.
6. Addressed feature engineering of the dataframe eventually to pivot the data onto Power BI desktop.
7. Relationship schema between different tables were created mainly for the "name" feature.
8. Calculated columns are added to the data in order for reporting of the requirements.
9. DAX Measures are created for specific requirements mentioned in the above,
10. Reports and Visualizations are generated finally with the help of DAX measures and features.

## Visuals and Reports
![image](https://github.com/sudhxan/Cricket-Dashboard-and-Reporting/assets/80266211/fe04a572-ed42-43e9-a184-e5d1e3b60d0f)

![image](https://github.com/sudhxan/Cricket-Dashboard-and-Reporting/assets/80266211/367552f6-08a7-4989-b9a6-66cddd9e9a68)

![image](https://github.com/sudhxan/Cricket-Dashboard-and-Reporting/assets/80266211/30c2bbc7-28d9-4ded-9ad3-e314b15eabbe)

#### Click on the .pbix file mentioned in the repository for more reports.


