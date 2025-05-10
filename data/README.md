# Data Files

This folder contains all raw and processed data used in the BAIS 3250 final project.

## Files

- `college_tuition_data.csv` – Scraped tuition data from U.S. public four-year colleges.
- `college_earnings_data.csv` – Median graduate earnings data obtained from the College Scorecard API.
- `merged_college_data.csv` – Final cleaned dataset combining tuition and earnings data, used for all analysis and modeling.

## Notes

- Tuition data was scraped using Selenium from university websites.
- Earnings data was retrieved using the College Scorecard API.
- Data cleaning and merging were completed using fuzzy string matching on institution names.
