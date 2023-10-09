# Data 512 Homework 1 - Professionalism and Reproducibility
Homework 1 for Human Centered Data Science class DATA 516

## Project Goal
---
The goal of the project is to extract and analyze monthly page view data from wikipedia on a list of Academy Award movies. There main deliverables for this project are three JSON data files and three separate data visualizations.

## Data Source
---
Wikimedia is listed under the Creative Commons Attribution Share-Alike license and the Wikimedia Foundation REST API terms of use can be found here: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

## API documentation:
---
- Pageviews API: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews
- Requests: https://requests.readthedocs.io/en/latest/
- Pandas: https://pandas.pydata.org/docs/
- Seaborn: https://seaborn.pydata.org/
- Matplotlib: https://matplotlib.org/stable/index.html

## Contents:
---
data_raw:
- thank_the_academy_AUG_2023.csv
    - This is the original data file provided by Dr. McDonald. It contains the names of each academy award winning movie and a corresponding wikipedia link.

data_final:
This is where the final data files are stored after extraction.
1. academy_monthly_mobile_201607-202309.json
    - monthly mobile page views per article (July 1, 2015 to September 30, 2023).
2. academy_monthly_desktop_201607-202309.json
    - monthly desktop page views per article (July 1, 2015 to September 30, 2023).
3. academy_monthly_cumulative_201607-202309.json
    - cumulative monthly page views per article for desktop and mobile (July 1, 2015 to September 30, 2023).

results:
This folder contains the three output visualizations.
1. Plot_1_Max_Min_Avg.png - the Maximum Average and Minimum Average plot
1. Plot_1_Top_10_Peaks.png - the Top 10 Peak Page Views plot
1. Plot_1_Top_10_Most_Recent.png - the Fewest Months of Data plot

## Notes
---
- Extracting the full movie dataset will take some time, for ~1000 movies for each access method (mobile-web, mobile-app, desktop) it took around 10 minutes.


## License:
---
Distributed under the MIT License. See `LICENSE` for more details.