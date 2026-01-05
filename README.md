# NETFLIX_DATABASE_USING_SQL
This project explores a Netflix dataset to perform insightful data analysis using SQL. The dataset contains detailed information about movies and TV shows, including title, type, director, cast, country, date_added, release_year, rating, duration, listed_in (genres), and description.


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/6ec53a2e-cfe9-4d29-b88f-a8766749cd83" />


Using PostgreSQL, this project covers key SQL concepts including filtering, sorting, grouping, aggregation, string manipulation, and handling multi-valued fields. Multi-valued columns such as cast and listed_in are split using string_to_array() and expanded into rows with UNNEST() and CROSS JOIN LATERAL. Functions like TRIM() are used to clean text, while aggregate functions like COUNT(), AVG(), and MAX() summarize data efficiently. Common Table Expressions (CTEs) are also used for structured and readable complex queries.

The project answers several practical questions, such as:

1.Number of Movies vs TV Shows

2.Content added in the last 5 years

3.Longest movie and TV show

4.Top genres by total content

5.Average release year per country

6.Movies in specific genres like Documentaries

7.Top cast members by number of titles

8.TV Shows with more than 5 seasons
