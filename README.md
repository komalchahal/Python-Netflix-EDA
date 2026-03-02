Netflix Exploratory Data Analysis (EDA) – Python Project

Project Overview:

This project performs Exploratory Data Analysis (EDA) on the Netflix dataset to identify content trends, genre distribution, rating patterns, and country-wise contributions.
The objective is to understand how Netflix’s content library has evolved over time and to extract meaningful business insights from the dataset.


Data Cleaning & Preparation

Filled missing values in the director and cast columns with "Unknown"
Converted the date_added column into proper datetime format for accurate time-series analysis
Performed basic data inspection using .info() and .isnull() to understand dataset structure and missing values
The dataset required minimal cleaning, as most columns were already well-structured.

Exploratory Analysis Performed:

Comparison of Movies vs TV Shows

Year-wise content addition trend

Top 10 countries contributing content

Content rating distribution

Top 10 most common genres

Key Insights:

Movies dominate the platform, forming a significantly larger portion of total content compared to TV Shows.
 
A sharp increase in content addition is observed after 2015, indicating rapid expansion of Netflix’s content library during this period.

The United States contributes the highest number of titles, making it the primary content-producing country on the platform.

International Movies and Dramas emerge as the most frequent genres, reflecting strong global and storytelling-driven content focus.

TV-MA is the most common content rating, suggesting a high volume of mature audience-oriented content.

Tools & Technologies Used:
Python
Pandas
NumPy
Matplotlib
Seaborn

Conclusion:

The analysis indicates that Netflix has strategically expanded its content library after 2015, with a strong emphasis on movies and mature-rated content. The dominance of U.S. titles highlights its primary production base, while the popularity of international movies reflects growing global content diversification. Overall, the data suggests a balanced mix of regional and international expansion strategies.
