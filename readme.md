# Google Play Store Apps & Reviews - Exploratory Data Analysis

This project explores Google Play Store data to discover patterns in app characteristics and user reviews.

## Datasets

1. **Google Play Store Dataset**
   - Contains information about apps (e.g., category, rating, reviews count, installs, size, type, price, content rating).

2. **User Reviews Dataset**
   - Contains translated app reviews with sentiment analysis results (e.g., translated review, sentiment polarity, sentiment subjectivity).

## Analysis

- Performed general EDA on both datasets individually (data cleaning, handling missing values, distributions).
- Conducted combined analysis after merging datasets on the `App` column.
- Focused on sentiment analysis of user reviews by rating categories, exploring polarity (positive/negative tone) and subjectivity (objective vs opinion-based).
- Visualized results using scatterplots and boxplots.

## Files

- `GooglePlayStore_EDA.ipynb` → Jupyter Notebook with full exploratory data analysis and visualizations.
- `googleplaystore.csv` → Dataset with app details.
- `googleplaystore_user_reviews.csv` → Dataset with app reviews and sentiment.

## How to Run

1. Clone the repository.
2. Open the notebook:
   ```bash
   jupyter notebook GooglePlayStore_EDA.ipynb

## Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
