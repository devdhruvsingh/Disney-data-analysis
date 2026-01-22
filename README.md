<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Disney Movies Box Office Analysis</title>
</head>
<body>

    <h1>Disney Movies Box Office Analysis (Python EDA)</h1>

    <h2>Project Overview</h2>
    <p>
        This project analyzes the box office performance of Disney movies using Python to understand how 
        <strong>genre</strong>, <strong>MPAA rating</strong>, and <strong>release timing</strong> influence revenue outcomes.
        The analysis emphasizes <strong>inflation-adjusted gross earnings</strong> to enable fair comparison across movies 
        released in different years. The primary focus of this project is exploratory data analysis (EDA) and 
        business insight generation rather than predictive modeling.
    </p>

    <h2>Dataset Description</h2>
    <p>The dataset contains historical Disney movie data with the following attributes:</p>
    <ul>
        <li>Movie title</li>
        <li>Release date</li>
        <li>Genre</li>
        <li>MPAA rating</li>
        <li>Total gross revenue</li>
        <li>Inflation-adjusted gross revenue</li>
    </ul>
    <p>
        Inflation-adjusted gross revenue was used as the primary performance metric throughout the analysis.
    </p>

    <h2>Tools &amp; Technologies</h2>
    <ul>
        <li>Python</li>
        <li>Pandas for data manipulation</li>
        <li>Matplotlib &amp; Seaborn for data visualization</li>
        <li>Jupyter Notebook for structured analysis</li>
    </ul>

    <h2>Data Preparation &amp; Feature Engineering</h2>
    <ul>
        <li>Converted release dates into datetime format</li>
        <li>Extracted release year for temporal analysis</li>
        <li>Standardized categorical values for consistency</li>
        <li>Prioritized inflation-adjusted gross over nominal gross values</li>
    </ul>

    <h2>Exploratory Data Analysis</h2>
    <p>
        The EDA was structured around business-driven questions and included:
    </p>
    <ul>
        <li>Distribution of movies by genre and MPAA rating</li>
        <li>Revenue performance comparison across genres</li>
        <li>Identification of the highest-earning movie within each genre</li>
        <li>Analysis of revenue distribution and outliers across genres and ratings</li>
        <li>Examination of the relationship between release year and inflation-adjusted revenue</li>
    </ul>
    <p>
        A combination of bar charts, box plots, scatter plots, heatmaps, and pie charts was used to uncover 
        performance patterns and revenue drivers.
    </p>

    <h2>Key Insights</h2>
    <ul>
        <li>A small number of blockbuster movies disproportionately contribute to total revenue within certain genres</li>
        <li>Family-friendly ratings (PG and PG-13) consistently outperform more restrictive ratings in inflation-adjusted earnings</li>
        <li>Some genres generate high total revenue but exhibit greater variability and financial risk</li>
        <li>Several older releases remain among top earners even after adjusting for inflation</li>
    </ul>

    <h2>Business Interpretation</h2>
    <p>
        The findings suggest that Disney’s box office success is strongly influenced by 
        <strong>genre selection</strong> and <strong>MPAA rating strategy</strong>. 
        While blockbuster-driven genres can deliver high returns, they also introduce higher volatility. 
        More consistent genres and family-oriented ratings may provide a more stable revenue foundation.
    </p>

    <h2>Limitations</h2>
    <ul>
        <li>Production and marketing costs were not available, preventing profitability analysis</li>
        <li>Genre classifications may overlap or oversimplify creative differences</li>
        <li>External factors such as competition and release windows were not included</li>
    </ul>

    <h2>Conclusion</h2>
    <p>
        This project demonstrates how Python-based exploratory data analysis can transform historical movie data 
        into actionable business insights. By combining data cleaning, feature engineering, and visualization-driven 
        analysis, the project highlights patterns that can support strategic decision-making in the entertainment industry.
    </p>

</body>
</html>
