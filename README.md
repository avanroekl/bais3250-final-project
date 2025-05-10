# BAIS:3250 Final Project – College ROI Analysis

This project analyzes the return on investment (ROI) of public four-year colleges in the United States by examining the relationship between tuition, graduation rates, location, and long-term graduate earnings.

The project includes data collection, cleaning, analysis, and machine learning modeling, all organized in separate, modular notebooks.

---

## Research Questions

1. **Does higher tuition correlate with higher graduate salaries?**
2. **Does graduation rate predict salary outcomes?**
3. **Are there regional differences in earnings among public four-year colleges?**
4. **Can institutional characteristics be used to predict graduate earnings using machine learning?**

---

## Project Structure

### `data/`
Raw and processed data files.
- `college_tuition_data.csv`
- `college_earnings_data.csv`
- `merged_college_data.csv`
- [`data/README.md`](./data/README.md)

### `notebooks/`
All Jupyter notebooks used for scraping, API pulls, merging, analysis, and modeling.
- `scrape_college_tuition.ipynb`
- `salary_data_API.ipynb`
- `merge_clean_datasets.ipynb`
- `college_roi_analysis.ipynb`
- `college_roi_machine_learning.ipynb`
- [`notebooks/README.md`](./notebooks/README.md)

### `final report/`
Final project deliverables.
- `Final Project Report.docx`
- [`final_report/readme.md`](./final-report/readme.md)

### Other Files
- [`data_dictionary.md`](./data_dictionary.md) – Description of all variables in the final dataset

---

## Data Sources

- [College Scorecard API](https://collegescorecard.ed.gov/data/documentation/)
- [College Tuition Compare](https://www.collegetuitioncompare.com/)

---

## Run Order

1. `notebooks/scrape_college_tuition.ipynb`
2. `notebooks/salary_data_API.ipynb`
3. `notebooks/merge_clean_datasets.ipynb`
4. `notebooks/college_roi_analysis.ipynb`
5. `notebooks/college_roi_machine_learning.ipynb`
