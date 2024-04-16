# Nettflix Data Project

# Tools Used: 
Excel, MySQL, Tableau

# Datasets :
https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies/data

# Business Problem:
Netflix wants to gather useful insights on their shows and movies for their subscribers through their datasets. The issue is, they are working with too much data (approximately 82k rows of data combined) and are unsure how to effectively analyze and extract meaningful insights from it. They need a robust and scalable data analytics solution to handle the vast amount of data and uncover valuable patterns and trends.

# How I Plan On Solving the Problem:
In helping Netflix gather valuable insights from their extensive movies and shows dataset, I will be utilizing Excel, SQL and a data visualization tool like PowerBI to extract relevant information, and conduct insightful analyses. By leveraging SQL's functions, I can uncover key metrics such as viewer ratings, popularity trends, genre preferences, and viewership patterns. Once the data has been extracted and prepared, I will leverage Tableau to present the findings. This will allow for interactive exploration of the data, enabling stakeholders at Netflix to gain actionable insights through visually appealing charts, graphs, and interactive visualizations. I plan on creating a dynamic dashboard in Tableau that enables users to delve into specific movie genres, viewer demographics, or geographical regions.


Here's how you can approach it:

# Data Acquisition:

- Download the Netflix dataset from Kaggle.
- Review the dataset to understand its structure and contents.

# Data Preparation:

Use Excel to clean and preprocess the data if needed. This might involve tasks like removing duplicates, handling missing values, or restructuring the data.
If the dataset is too large or complex for Excel alone, consider using SQL to perform data cleaning and transformation tasks. You can import the dataset into a SQL database (like MySQL, PostgreSQL, or SQLite) and write SQL queries to clean and transform the data.

# Data Analysis:

Utilize SQL for more advanced data analysis tasks. You can write queries to extract insights from the dataset, such as finding the most popular genres, directors, or actors, or analyzing trends over time.
Excel can also be used for data analysis, especially for creating pivot tables, charts, and performing statistical analysis.
 
# Data Visualization:

Power BI is excellent for creating interactive and visually appealing dashboards and reports. You can connect Power BI to your dataset (either directly or via SQL), and then create various visualizations to showcase your findings.
Use Power BI's features like filters, slicers, and drill-downs to allow users to explore the data dynamically.

# Presentation and Insights:

Once you have created your analysis and visualizations, compile them into a presentation or report.
Highlight key insights and findings from your analysis.
Consider adding commentary or annotations to your visualizations to provide context.
Iterate and Refine:

# Review your project and gather feedback from others.
Iterate on your analysis and visualizations based on the feedback received.
Refine your project to ensure it effectively communicates the insights derived from the Netflix dataset.

# Questions I Wanted To Answer From the Dataset:
-- Which movies and shows on Netflix ranked in the top 10 and bottom 10 based on their IMDB scores?

- Bottom 10 Movies

- Bottom 10 Shows


-- How many movies and shows fall in each decade in Netflix's library?

-- How did age-certifications impact the dataset?

-- Which genres are the most common?

-- What were the top 10 movies according to IMDB score?

-- What were the top 10 shows according to IMDB score? 

-- What were the bottom 10 movies according to IMDB score? 

-- What were the bottom 10 shows according to IMDB score? 

-- What were the average IMDB and TMDB scores for shows and movies? 

-- Count of movies and shows in each decade

-- What were the average IMDB and TMDB scores for each production country?

-- What were the average IMDB and TMDB scores for each age certification for shows and movies?

-- What were the 5 most common age certifications for movies?

-- Who were the top 20 actors that appeared the most in movies/shows? 

-- Who were the top 20 directors that directed the most movies/shows? 

-- Calculating the average runtime of movies and TV shows separately

-- Finding the titles and  directors of movies released on or after 2010

-- Which shows on Netflix have the most seasons?

-- Which genres had the most movies? 

-- Which genres had the most shows? 

-- Titles and Directors of movies with high IMDB scores (>7.5) and high TMDB popularity scores (>80) 

-- What were the total number of titles for each year? 

-- Actors who have starred in the most highly rated movies or shows

-- Which actors/actresses played the same character in multiple movies or TV shows? 

-- What were the top 3 most common genres?

-- Average IMDB score for leading actors/actresses in movies or shows 
