This Power BI project focuses on analyzing a dataset of Netflix movies to discover trends in movie ratings, runtimes, release timelines, and age certifications. The dashboard provides a comprehensive view of various movie characteristics, giving insights into viewer preferences, movie duration, and rating trends over time.

![image-1](https://github.com/user-attachments/assets/bf4ab5d2-d87e-45db-9815-09c2f16f401a)
---

Objective

The goal of this project is to explore and analyze Netflix movie data, helping stakeholders understand trends and make data-driven decisions related to the movie industry. The analysis reveals insights into movie ratings, age certifications, runtimes, and their evolution over the years.


---

Key Insights

1. Movie Rating Over Timeline:

This line chart visualizes how average movie ratings have changed over time, providing a historical perspective on how viewer ratings evolved across different decades.



2. Top 20 Highly Rated Movies:

A bar chart shows the top 20 highest-rated movies based on the number of votes received. This provides insights into which movies gained the most audience approval.



3. Average Runtime of Movies:

This bar chart displays the average runtime for various movies, helping to understand the duration trends in popular movies.



4. Number of Movies by Age Certification:

This column chart provides a breakdown of movies by age certification (e.g., R, PG-13, PG), allowing for an analysis of the distribution of movies based on content suitability for different age groups.



5. Number of Movies and Ratings Over Timeline:

A combination of a line chart and a count of movies shows the relationship between the number of movies released and their average ratings over the years, illustrating peaks and dips in both movie production and audience response.





---

Data Cleaning and Transformation

1. Data Cleaning:

Using Power BI’s Power Query Editor, I performed data cleaning tasks such as removing duplicates, handling missing values, and formatting columns like movie runtimes and release dates.



2. Data Transformation:

I used DAX formulas to calculate additional fields, such as the average runtime and rating scores for movies. Relationships were built between different columns to allow for effective filtering and cross-referencing within visualizations.





---

Visualizations

1. Line Chart:

Used to show the ratings over time and the number of movies released each year, enabling the comparison between movie popularity and production trends.



2. Bar Charts:

Used to display the top 20 rated movies and the average runtime of movies, providing a comparative analysis.



3. Column Chart:

The age certification distribution is visualized using a column chart, making it easy to see the spread of movies by age rating.





---

Tools and Techniques Used

Power BI: The primary tool used for building data models, creating relationships, and generating interactive visualizations.

DAX (Data Analysis Expressions): Utilized for creating calculated columns, measures, and dynamic data filtering.

Power Query Editor: Used for data cleaning, transformation, and modeling tasks.



---

Challenges and Solutions

1. Handling Missing Data:

Missing age certification and rating data were handled by replacing missing values with default placeholders or using average values for analysis.



2. Optimizing Performance:

As the dataset grew, I optimized the data model by eliminating unnecessary columns and applying filters to improve dashboard performance and responsiveness.





---

Future Enhancements

1. Genre-Based Analysis:

Adding genre-based filtering options to allow users to drill down into specific movie categories (e.g., action, drama, comedy).



2. Advanced KPIs:

Including KPIs (Key Performance Indicators) for deeper insights into movie trends and viewer engagement over time.





---

Conclusion

This Netflix Movie Data Analysis project in Power BI provides a robust, interactive dashboard that highlights key trends in the movie industry. It enables users to quickly explore top-rated movies, rating trends over time, runtime patterns, and distribution by age certification, making it a useful tool for analysts, movie enthusiasts, and industry stakeholders.
