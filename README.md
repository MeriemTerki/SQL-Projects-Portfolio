# 📊 SQL-Projects-Portfolio
A collection of SQL projects to make in practice the needed skills in SQL as a data professional

## The World Bank's International Debt Data Analysis 🌐💰

#### Introduction 🌍
In the complex web of global economics, countries often resort to taking on debt to manage their necessities and economic stability. The World Bank, a major player in this arena, provides crucial debt to developing nations. This notebook delves into The World Bank's international debt data, exploring the total debt, distinct countries, debt indicators, and more.

#### Dataset 📊
The dataset unravels information about the debt owed by developing countries, categorizing it across various indicators. Through SQL queries, we aim to answer key questions such as the total debt, countries with the highest debt, average debt across indicators, and common debt issues.

#### Objectives 📈
1. **Explore International Debt Data**: Connect to the international_debt database, select and display the first ten rows of the dataset.
2. **Count Distinct Countries**: Determine the number of distinct countries present in the dataset.
3. **Discover Distinct Debt Indicators**: Identify the distinct debt indicators present in the dataset.
4. **Total Debt Owed Globally**: Calculate the total amount of debt owed by all countries.
5. **Country with the Highest Debt**: Find the country with the highest total debt and the corresponding amount.
6. **Average Debt Across Indicators**: Explore the average amount of debt owed by countries across different indicators.
7. **Highest Principal Repayments**: Identify the indicator with the highest average debt, focusing on principal repayments.
8. **Most Common Debt Indicator**: Find the most common debt indicator across countries.
9. **Other Viable Debt Issues and Conclusion**: Explore other potential debt issues by identifying the maximum amount of debt each country has.
    
#### Key Learning 🧠

##### SQL Syntax Mastery
- **SELECT Statements**: Utilizing `SELECT` statements to retrieve specific columns and rows from the dataset.
- **LIMIT Clause**: Employing the `LIMIT` clause to restrict the number of rows returned by a query.
- **ORDER BY Clause**: Organizing query results using the `ORDER BY` clause for meaningful presentation.
- **WHERE Clause**: Filtering data based on specified conditions using the `WHERE` clause.

##### SQL Functions Expertise
- **Aggregate Functions**: Leveraging aggregate functions like `AVG`, `COUNT`, and `SUM` for comprehensive data analysis.
- **ROUND Function**: Applying the `ROUND` function to control the precision of numerical values in the results.
- **DISTINCT Keyword**: Using the `DISTINCT` keyword to eliminate duplicate values in query results.

##### SQL Joins Proficiency
- **INNER JOIN Operation**: Performing `INNER JOIN` operations to combine data from multiple tables based on matching columns.
- **LEFT JOIN Operation**: Employing `LEFT JOIN` to retrieve all records from the left table and matching records from the right table.
- **Subqueries**: Integrating subqueries to achieve more complex data retrieval and comparisons.

##### Set Operations Play
- **EXCEPT Operation**: Employing the `EXCEPT` operation for dataset subtraction, identifying differences between two result sets.
- **INTERSECT Operation**: Using the `INTERSECT` operation to find common elements between two result sets.

View my project [here](https://github.com/MeriemTerki/SQL-Projects-Portfolio/blob/main/Analyze%20International%20Debt%20Statistics/Analyze-International-Debt-Statistics.ipynb).

## Analyzing American Baby Name Trends👶

#### Introduction 🌍
Understanding the evolution of baby names over the years is not only interesting for new parents but also holds broader significance for businesses in various industries. In this project, we aim to analyze American baby name trends using data provided by the United States Social Security Administration. 

#### Dataset 📊
The dataset spans 101 years, from 1920 through 2020, and includes first names, the number of babies given each name in a year, and the gender of those babies.

#### Objectives 🚀
1. **Identify Timeless Names**: Explore names that have stood the test of time by selecting names that have been given to babies in all 101 years. This analysis provides insights into classic American names that have maintained popularity over the decades.
2. **Classify Popularity Types**:Classify names as 'Classic', 'Semi-classic', 'Semi-trendy', or 'Trendy' based on the duration of their popularity. This classification will help us understand the type of popularity each name in the dataset has enjoyed.
3. **Top-ranked Female Names**:Rank and display the top 10 female names based on the total number of babies given each name since 1920. This analysis focuses on traditionally female names.
4. **Pick a Baby Name**: Assist a friend in choosing a baby name for her daughter. The criteria include the name being traditionally female, ending in the letter 'a', and having been popular since 2015. Explore and provide options based on these criteria.
5. **The Olivia Expansion**:  Investigate the popularity of the name 'Olivia' over the years, including when it gained prominence. Utilize window functions to analyze the cumulative number of babies named Olivia from 1991 to the present.

#### Learning Focus 🧠

- **SQL Window Functions**: Mastering the use of window functions (`RANK()` in this case) to perform calculations across a set of table rows.

- **Common Table Expressions (CTEs)**: Utilizing CTEs to break down complex queries into modular, more understandable parts.

- **Conditional Classification**: Employing `CASE` statements for conditional logic to classify data into different categories.

View my project [here](https://github.com/MeriemTerki/SQL-Projects-Portfolio/blob/main/When-Was-the-Golden-Age-of-Video-Games.ipynb).

## Video Game Analysis Project 🎮

#### Introduction 🌍
This project dives into the realm of top-selling video games from 1977 to 2020, unraveling trends, critical reception, and player preferences. The dataset, featuring the top 400 best-selling games, unveils insights through game sales and comprehensive reviews.

#### Dataset 📊
The dataset is a treasure trove from the gaming industry, spotlighting the top 400 best-selling video games. Two tables, `game_sales` and `reviews`, provide a comprehensive view. `game_sales` showcases game details like name, platform, sales, and release year. The `reviews` table unfolds critic and user scores for a holistic analysis.

#### Objectives 🚀
1. **Top Selling Games**: Uncover and celebrate the top ten best-selling video games of all time.
2. **Missing Review Scores**: Address the mystery of missing review scores for some games.
3. **Years That Critics Loved**: Time-travel through the years with the highest average critic scores, seeking the golden age of gaming.
4. **Verification of Critic Favorites**: Uncover the truth behind suspiciously round average critic scores, delving into the number of reviewed games.
5. **Years That Dropped Off Critics' Favorites List**: Discover the overlooked years due to minimal game reviews.
6. **Years Video Game Players Loved**: Decode player preferences through average user scores by year.
7. **Years That Both Players and Critics Loved**: Identify the golden years that captured both critic and player hearts.
8. **Sales in the Best Video Game Years**: Peek into the financial success of years cherished by critics and players alike.

#### Key Learning 🧠
- **SQL Syntax**: Mastering SQL queries for effective data retrieval and analysis.
- **SQL Functions**: Employing functions like `AVG`, `COUNT`, `SUM`, and `ROUND` for insightful data summaries.
- **SQL Joins**: Weaving together information from diverse sources with join operations.
- **Set Operations**: Playing with set operations (`EXCEPT` and `INTERSECT`) for nuanced dataset comparisons.

View my project [here](https://github.com/MeriemTerki/SQL-Projects-Portfolio/blob/main/When-Was-the-Golden-Age-of-Video-Games.ipynb).





