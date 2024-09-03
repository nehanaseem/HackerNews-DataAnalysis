# Hacker News Data Analysis

Welcome to the Hacker News Data Analysis repository! This project focuses on analyzing post engagement on Hacker News, specifically examining the number of comments and their relationship to the time of posting.

## Dataset

The analysis is based on the `hacker.csv` dataset, which contains the following columns:

- **id**: Unique identifier for each post
- **title**: Title of the post
- **url**: URL of the post
- **num_points**: Number of points the post received
- **num_comments**: Number of comments the post received
- **author**: Author of the post
- **created_at**: Timestamp when the post was created

## Project Overview

This project covers the following key areas:

1. **Data Preprocessing**:
    - Converted the `created_at` column to datetime format.
    - Extracted the hour from the `created_at` timestamp.
    - Standardized titles by converting them to lowercase.
    - Filtered posts to focus on those starting with "Ask HN" and "Show HN".

2. **Descriptive Statistics**:
    - Calculated the average number of comments for "Ask HN" and "Show HN" posts.
    - Identified the maximum number of comments received on a single post.

3. **Time-Based Analysis**:
    - Grouped data by the hour of creation to calculate the average number of comments.
    - Determined the hour with the highest engagement based on comment count.
    - Analyzed the top 5 hours for "Ask HN" and "Show HN" posts.

4. **Pivot Table**:
    - Created a pivot table to further analyze the average comments for "Ask HN" posts by hour.

## Key Findings

- **Peak Hours**: The analysis reveals specific hours when posts receive the most comments, providing insights into optimal posting times.
- **Engagement Trends**: "Ask HN" and "Show HN" posts exhibit different engagement patterns, which can inform content strategy on Hacker News.

## How to Use

To reproduce this analysis, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/HackerNews-DataAnalysis.git
   pip install pandas
   python analysis.py
   
## Conclusion
This project offers a deep dive into Hacker News engagement, with practical insights into when and how to post for maximum interaction. It serves as a useful resource for content creators, marketers, and data enthusiasts interested in social media analytics.
