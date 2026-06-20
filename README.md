 Impact of Batter-Friendly Conditions on IPL Scoring Trends (2008–2025)

 Project Overview

This project investigates whether the Indian Premier League (IPL) has become increasingly batter-friendly between 2008 and 2025.

Using ball-by-ball IPL data, I analyzed scoring trends, run rates, boundary frequency, bowling effectiveness, and match outcomes to determine whether modern IPL conditions favor batters more than earlier seasons.


Objective

To analyze whether IPL cricket has become significantly more batter-friendly over time using historical IPL data.


 Research Questions

- Has the average innings score increased over time?
- Has the average run rate increased over time?
- Are more sixes being hit than before?
- Has bowling become less effective?
- Have 200+ scores become more common?
- Which venues are the most batting-friendly?


 Dataset

 matches.csv

Contains:
- Season
- Venue
- Teams
- Match Result

deliveries.csv

Contains:
- Ball-by-ball information
- Runs scored
- Wickets
- Boundaries

Source: Kaggle IPL Dataset


 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- Jupyter Notebook


 Methodology

 Data Cleaning

- Removed unnecessary columns
- Checked missing values
- Standardized season information

 Feature Engineering

Created:

- Average innings score by season
- Run rate by season
- Sixes per season
- Economy rate by season
- Number of 200+ totals
- Venue-wise average scores

 Batter Friendliness Index (BFI)

Developed a custom Batter Friendliness Index (BFI) by combining:

- Average innings score
- Run rate
- Six-hitting frequency
- Bowling economy rate

All metrics were normalized using MinMax Scaling and combined into a single score.

Dashboard

 Page 1: IPL Scoring Trends

- KPI Cards
- Average Score Trend
- Run Rate Trend
- Economy Trend
- BFI Trend

 Page 2: Power Hitting & Venue Analysis

- Sixes Trend
- 200+ Totals Trend
- Top Batting-Friendly Venues


 Key Findings

- Average innings scores increased significantly.
- Run rates increased over time.
- Six-hitting frequency increased substantially.
- Bowling economy rates increased.
- 200+ scores became more common.
- Batter Friendliness Index showed a strong upward trend.


Conclusion

The analysis provides strong evidence that IPL has become increasingly batter-friendly between 2008 and 2025.

Higher scores, faster run rates, increased six-hitting frequency, and rising bowling economy rates collectively support this conclusion.


Future Improvements

- Weather analysis
- Pitch condition analysis
- Boundary size analysis
- Team strategy analysis
- Predictive score forecasting models
