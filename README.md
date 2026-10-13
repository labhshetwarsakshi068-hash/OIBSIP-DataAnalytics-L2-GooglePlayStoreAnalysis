# Google Play Store Data Analysis

## Project Overview
This project analyzes Google Play Store applications and user reviews using Python. It explores app categories, ratings, installs, pricing, and review sentiment to identify useful patterns.

## Datasets
- `googleplaystore.csv` — application details.
- `googleplaystore_user_reviews.csv` — user reviews and sentiment information.

Both datasets were obtained from the Google Play Store Apps dataset on Kaggle.

## Tools and Libraries
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook

## Data Cleaning
- Removed duplicate application records.
- Converted rating, review count, installs, and price into numeric formats.
- Removed app records with missing essential fields.
- Removed reviews with missing review text or sentiment.
- Removed duplicate review records.

## Key Findings
- Original apps dataset: 10,841 rows.
- Cleaned apps dataset: 8,892 rows.
- Original reviews dataset: 64,295 rows.
- Cleaned reviews dataset: 29,692 rows.
- Average app rating: 4.19.
- Free apps: 8,279.
- Paid apps: 613.
- Average rating of free apps: 4.18.
- Average rating of paid apps: 4.26.
- Positive reviews: 64.04%.
- Negative reviews: 21.29%.
- Neutral reviews: 14.67%.
- Average review sentiment polarity: 0.189.

The FAMILY category contains the highest number of apps in the cleaned dataset. Several apps have install counts of one billion or more.

## Visualizations
The notebook includes:
1. Top app categories by number of apps.
2. Distribution of app ratings.
3. Free versus paid apps.
4. User review sentiment distribution.
5. Price distribution of paid apps.
6. Review sentiment polarity distribution.

## How to Run
1. Download both CSV datasets and place them in the project folder.
2. Install the required libraries:
   `pip install pandas numpy matplotlib seaborn jupyter`
3. Open Jupyter Notebook.
4. Run `Google_PlayStore_Analysis.ipynb` from top to bottom.

## Conclusion
The analysis shows that free apps dominate the cleaned dataset and that positive reviews form the largest sentiment group. The results provide an overview of app categories, ratings, installs, pricing, and user feedback.

## Note
This is an exploratory data analysis project. The findings describe the available datasets and do not establish causal relationships.
