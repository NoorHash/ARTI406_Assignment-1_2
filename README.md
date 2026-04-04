# ML---Assignment-1
# Exploratory Data Analysis (EDA) on YouTube Trending Dataset

## Dataset Source
The dataset was obtained from Kaggle:
https://www.kaggle.com/datasets/datasnaek/youtube-new

## Dataset Description
The dataset contains trending YouTube video data collected from multiple countries such as the United States, United Kingdom, Canada, and others. Each country has a separate dataset file with similar structure and features.

In this project, the United States dataset (USvideos.csv) was selected to perform the analysis. This allows for a focused and consistent exploration of video popularity and user engagement.

## Dataset Size
The dataset contains approximately:
- Number of rows: [PUT YOUR ROWS]
- Number of columns: [PUT YOUR COLUMNS]

## Features Description
- video_id: Unique identifier for each video  
- title: Title of the video  
- channel_title: Name of the YouTube channel  
- category_id: Category ID of the video  
- publish_time: Time the video was published  
- views: Number of views  
- likes: Number of likes  
- dislikes: Number of dislikes  
- comment_count: Number of comments  
- comments_disabled: Indicates if comments are disabled  
- ratings_disabled: Indicates if ratings are disabled  
- video_error_or_removed: Indicates if the video is unavailable  

## Purpose of the Dataset
The purpose of this dataset is to analyze video performance and audience engagement on YouTube. The analysis aims to identify patterns, trends, and relationships between variables such as views, likes, and comments.

## Data Cleaning
Data cleaning was performed within the Jupyter Notebook. The following steps were applied:
- Converted date columns into datetime format  
- Checked and removed duplicate rows  
- Verified missing values  
- Created new features such as month and year  

## Visualizations and Insights
Several visualizations were created to explore the data, including:
- Histograms to analyze distributions of views, likes, and comments  
- Scatter plots to study relationships between variables  
- Bar charts to compare categories and channels  
- Heatmap to analyze correlations  

The analysis revealed that:
- Most videos have low engagement, while a few videos go viral  
- There is a strong positive relationship between views, likes, and comments  
- Some categories and channels perform better than others  
- Video popularity directly influences user engagement  

## Note
Due to file size limitations on GitHub, ه i uploaded a zip file instead.
