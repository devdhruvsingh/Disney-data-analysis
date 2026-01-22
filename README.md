📽️ Disney Movies Box Office Analysis (Python EDA)
Project Overview
This project analyzes the box office performance of Disney movies using Python to understand how genre, MPAA rating, and release timing influence revenue outcomes. The analysis emphasizes inflation-adjusted gross earnings to enable fair comparison across movies released in different years. The focus of the project is exploratory data analysis (EDA and business insight generation rather than predictive modeling.
Dataset Description
The dataset consists of historical Disney movie data with the following attributes:
Movie title
Release date
Genre
MPAA rating
Total gross revenue
Inflation-adjusted gross revenue
Inflation-adjusted gross was used as the primary performance metric throughout the analysis.
Tools & Technologies
Python
Pandas for data manipulation
Matplotlib & Seaborn for data visualization
Jupyter Notebook for structured analysis
Data Preparation & Feature Engineering
Converted release dates into datetime format
Extracted release year for temporal analysis
Standardized categorical values for consistency
Prioritized inflation-adjusted gross over nominal gross values
Exploratory Data Analysis
The EDA was structured around business-driven questions and included:
Distribution of movies by genre and MPAA rating
Revenue performance comparison across genres
Identification of the highest-earning movie within each genre
Analysis of revenue distribution and outliers across genres and ratings
Examination of the relationship between release year and inflation-adjusted revenue
A combination of bar charts, box plots, scatter plots, heatmaps, and pie charts was used to uncover patterns and revenue drivers.
Key Insights
A small number of blockbuster movies disproportionately contribute to total revenue within certain genres
Family-friendly ratings (PG and PG-13) consistently outperform more restrictive ratings in inflation-adjusted earnings
Some genres generate high total revenue but exhibit greater variability and financial risk
Several older releases remain among top earners even after adjusting for inflation
Business Interpretation
The findings suggest that Disney’s box office success is strongly influenced by genre selection and MPAA rating strategy. While blockbuster-driven genres can deliver high returns, they also introduce higher volatility. More consistent genres and family-oriented ratings may provide a more stable revenue foundation.
Limitations
Production and marketing costs were not available, preventing profitability analysis
Genre classifications may overlap or oversimplify creative differences
External factors such as competition, release windows, and distribution strategies were not included
Conclusion
This project demonstrates how Python-based exploratory data analysis can be used to transform historical movie data into actionable business insights. By combining data cleaning, feature engineering, and visualization-driven analysis, the project highlights patterns that can support strategic decision-making in the entertainment industry.
