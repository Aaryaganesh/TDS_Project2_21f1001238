# Automated Analysis Report

## Summary
{'columns': ['date', 'language', 'type', 'title', 'by', 'overall', 'quality', 'repeatability'], 'data_types': {'date': dtype('O'), 'language': dtype('O'), 'type': dtype('O'), 'title': dtype('O'), 'by': dtype('O'), 'overall': dtype('int64'), 'quality': dtype('int64'), 'repeatability': dtype('int64')}, 'missing_values': {'date': 99, 'language': 0, 'type': 0, 'title': 0, 'by': 262, 'overall': 0, 'quality': 0, 'repeatability': 0}, 'summary_stats': {'date': {'count': 2553, 'unique': 2055, 'top': '21-May-06', 'freq': 8, 'mean': nan, 'std': nan, 'min': nan, '25%': nan, '50%': nan, '75%': nan, 'max': nan}, 'language': {'count': 2652, 'unique': 11, 'top': 'English', 'freq': 1306, 'mean': nan, 'std': nan, 'min': nan, '25%': nan, '50%': nan, '75%': nan, 'max': nan}, 'type': {'count': 2652, 'unique': 8, 'top': 'movie', 'freq': 2211, 'mean': nan, 'std': nan, 'min': nan, '25%': nan, '50%': nan, '75%': nan, 'max': nan}, 'title': {'count': 2652, 'unique': 2312, 'top': 'Kanda Naal Mudhal', 'freq': 9, 'mean': nan, 'std': nan, 'min': nan, '25%': nan, '50%': nan, '75%': nan, 'max': nan}, 'by': {'count': 2390, 'unique': 1528, 'top': 'Kiefer Sutherland', 'freq': 48, 'mean': nan, 'std': nan, 'min': nan, '25%': nan, '50%': nan, '75%': nan, 'max': nan}, 'overall': {'count': 2652.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 3.0475113122171944, 'std': 0.7621797580962717, 'min': 1.0, '25%': 3.0, '50%': 3.0, '75%': 3.0, 'max': 5.0}, 'quality': {'count': 2652.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 3.2092760180995477, 'std': 0.7967426636666686, 'min': 1.0, '25%': 3.0, '50%': 3.0, '75%': 4.0, 'max': 5.0}, 'repeatability': {'count': 2652.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 1.4947209653092006, 'std': 0.598289430580212, 'min': 1.0, '25%': 1.0, '50%': 1.0, '75%': 2.0, 'max': 3.0}}}

## Story
Based on the analysis conducted on the dataset `media.csv`, several key observations and insights have emerged regarding the characteristics and distribution of the data. 

### Overview of Dataset
The dataset consists of 2,652 entries with several attributes associated with media items, including the `date`, `language`, `type`, `title`, the author or creator (`by`), and various ratings such as `overall`, `quality`, and `repeatability`. Notably, the dataset contains missing values, particularly in the `by` column, where 262 entries lack this information. The `date` column also has 99 missing values, indicating the potential need for imputation or exclusion of these records in further analyses.

### Categorical Data Insights
#### Language
The dataset showcases a diverse mix of languages, with 'English' being the most prevalent, accounting for 1,306 entries of the total 2,652. This suggests that English-language media is more extensively represented compared to other languages. 

#### Type
Regarding the media type, the dataset is heavily skewed towards movies, comprising 2,211 entries. This indicates that the dataset primarily captures cinematic works, with other media types being significantly less represented.

#### Title and Creator
The unique titles in the dataset amount to 2,312, with the most recurring title, "Kanda Naal Mudhal," appearing 9 times. Similarly, the creator or contributor 'Kiefer Sutherland' is noted as the most frequent individual in the dataset with 48 mentions. This underlines the presence of certain popular titles and contributors in the media landscape.

### Numerical Data Analysis
The numerical ratings across the dataset reveal the following:

- **Overall Ratings**: The average overall rating is approximately 3.05, suggesting a slightly above-average perception among users. The distribution appears to center around this average, as indicated by a high frequency of ratings at 3.
- **Quality Ratings**: The average quality rating stands at about 3.21, which also signifies a favorable evaluation compared to the overall ratings. This may imply that while the media are generally well-received, perceptions of quality might be slightly higher than overall satisfaction.
- **Repeatability Ratings**: The average repeatability rating is around 1.49, indicating that repeat viewership or engagement is relatively low, with the most common rating being 1. This suggests that once viewed, media are not frequently revisited by audiences. 

### Correlation Analysis
The correlation analysis indicated certain relationships among the numerical variables:
- A positive correlation between overall and quality ratings suggests that higher quality media generally receive better overall ratings.
- Conversely, the relationship between overall ratings and repeatability seems weaker, indicating that high-rated media may not necessarily translate to repeated viewership.

### Visualizations
- **Histogram**: The histogram for numerical ratings illustrated a left-skewed distribution for overall and quality ratings, with peaks at values of 3 and 4, showing that most media falls within an acceptable range but does not often reach the highest ratings.
- **Bar Plots**: Bar plots for categorical data showcased the dominance of movies and the English language, highlighting the need for more variety in the dataset, particularly in terms of type and language representation.

### Conclusion
Overall, the dataset provides a nuanced view of how media is being rated across different factors. The analysis reveals a generally positive sentiment among users, especially regarding quality, albeit with indications of low repeat engagement. Future work may focus on addressing missing data, deepening the analysis of correlation between different fields, and exploring user demographics to gain a more comprehensive understanding of media preferences.

## Visualizations
![Visualization](media\heatmap.png)
![Visualization](media\boxplot_overall.png)
![Visualization](media\histogram_overall.png)
