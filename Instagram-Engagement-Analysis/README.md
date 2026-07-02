# Instagram Engagement Analysis

## Project Overview

This project was completed as part of the **Alfido Tech Internship**. The objective was to analyze Instagram engagement data to identify content performance patterns, hashtag effectiveness, follower trends, and engagement insights. Based on the analysis, recommendations were developed to improve Instagram content strategy.

## Dataset

* **Source:** Kaggle – Instagram Dataset
* **Files Used:**

  * likes.csv
  * follows.csv
  * tags.csv
  * comments.csv
  * photo_tags.csv
  * users.csv
  * photos.csv

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Steps Performed

* Loaded and explored the dataset
* Cleaned column names and checked for missing values
* Converted date columns into datetime format
* Performed exploratory data analysis (EDA)
* Created visualizations to study:

  * Content type distribution
  * Instagram filter usage
  * Like reaction types
  * Average likes by content type
  * Comments by hashtag usage
  * Follower distribution
* Generated insights and strategic recommendations

## Key Findings

* Photos were the most common content type.
* Photo posts received slightly higher average likes.
* Posts using two hashtags generated the highest number of comments.
* Most posts used Instagram filters.
* Follower distribution was relatively balanced.

## Limitations

* All posts had the same timestamp (8:04 AM), making posting-time analysis impossible.
* The dataset appears to be synthetic, so conclusions are limited to this dataset.

## Recommendations

* Prioritize photo-based content.
* Use approximately two relevant hashtags.
* Maintain a consistent posting schedule.
* Monitor engagement metrics regularly.
* Use real-world Instagram analytics for future improvements.

## How to Run

1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install the required Python libraries if needed.
4. Run all cells sequentially to reproduce the analysis.

## Project Structure

```text
Instagram-Engagement-Analysis/
│
├── Instagram_Analysis.ipynb
├── README.md
├── Strategy_Document.pdf
├── images/
└── Dataset (or Kaggle dataset link)
```
