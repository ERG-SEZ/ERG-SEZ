# Covid Project - SQL Analysis

## Introduction
This project uses SQL to analyze data related to the Covid pandemic. Two tables were used - coviddeaths and covidvaccinations - to calculate key metrics such as infection rates, death rates, and vaccination rates.

## Installation
To run this project, you'll need access to a SQL database and the ability to execute SQL queries. The two tables used in this project - coviddeaths and covidvaccinations - will need to be imported into your database before running the queries.

## Usage
This project includes several SQL queries that can be run to analyze Covid data. Here are some examples:

SELECT * FROM coviddeaths WHERE continent IS NOT NULL ORDER BY location, date; - this query retrieves all data from the coviddeaths table, but excludes any rows where continent is null. The resulting data is sorted by location and date.

SELECT location, date, total_cases, total_deaths, ROUND((total_deaths / total_cases) * 100, 2) AS death_percentage FROM coviddeaths WHERE location = 'Turkey' ORDER BY date; - this query calculates the probability of dying from Covid in Turkey, based on the total number of cases and deaths.

SELECT location, population, MAX(total_cases) AS highest_infection_count, ROUND(MAX((total_cases / population)) * 100, 2) AS percent_population_infected FROM coviddeaths GROUP BY location, population ORDER BY percent_population_infected DESC; - this query identifies the countries with the highest infection rates, based on the total number of cases and population size.

These are just a few examples of the queries included in this project. You can modify these queries or create your own to analyze the Covid data in different ways.

Credits
This project was created by [Your Name]. Feel free to contact me with any questions or feedback!

Resume
[Include your resume here]
































# A Comprehensive Analysis of Sales and Profit

The aim of this project is to analyze the sales and profit trends of a company's products over time. Through various data visualizations and analysis, we provide insights on the top products by sales and profit, the most selling products, the most selling category and sub-category, the most profitable category and sub-category, the most preferred ship mode, the top countries and markets by sales, and recommendations to improve the overall sales and profit of the company.





## Conclusions
### Questions
* What is the sales and the profit trend over time?
* What are the top 10 products by sales and by profit?
* What are the most selling products?
* Which are the most selling category and sub-category?
* Which are the most profittable category and sub-category?
* Which is the most preferred ship mode?
* What are the top countries and markets by sales ?

### Recommendations

The overall trend for both sales and profit is positive, which is a good sign for the company. However, the company should monitor the sales and profit trends for each month to identify any patterns or changes that need to be addressed.

The company should focus on the top-selling products and categories to maximize their profits. The technology category is the most important category for both sales and profits, so the company should invest in promoting and selling more technology products. Phones are the most important sub-category for both sales and profits, so the company should focus on improving sales and profits for this sub-category.

The most selling products and sub-categories should be monitored closely. Staples, Cardinal Index Tab, and Eldon File Cart are the most selling products, and Binders and Storage are the best selling sub-categories. The company should ensure that they maintain a sufficient inventory of these products and sub-categories to meet the customer demand.

The company should focus on improving the profitability of the Furniture category, which is currently the least profitable category. They can achieve this by identifying the reasons for the low profitability and taking corrective actions.

The company should continue to monitor the profitability of the Copiers and Phones sub-categories, which are the most profitable sub-categories. They can focus on promoting and selling more products in these sub-categories to maximize their profits.

The company could also review their shipping and delivery strategies, to ensure that the most preferred shipping mode (Standard Class) is optimized to improve customer satisfaction and minimize shipping costs.

There is an overall upward trend in sales and profit, the company could continue to focus on expanding their sales channels and targeting potential customers in the high performing regions, such as APAC, EU and US.

## Conclusions

1. How is the number of content added to Netflix changed over time?
   - The number of movies and TV shows added to Netflix has generally increased over time, with a significant spike in 2017, 2018, and 2019.
   - In 2019 and 2020, there were a similar number of TV shows added, with over 500 new shows added in both years. In 2021, the number of TV shows decreased for the first time after the upward trend.
   - Additionally, in 2020 and 2021, the number of movies added to the platform decreased slightly compared to the previous year.

2. What is the percentage of TV Show and Movie on Netflix?
   - The percentage of movies is 69.7% of the total types and this is more than double the percentage of TV shows in the total types.
   - The percentage of TV shows is 30.3% of the total types.

3. In which months is more content being added to Netflix?
   - The months with the highest number of content additions are July and December, with 827 and 812 additions, respectively.
   - The month with the lowest number of content additions is February, with 562 additions.

4. Which rating is the highest on Netflix?
   - The rating with the largest number of content titles is TV-MA, which is content intended for adult viewers and may be unsuitable for children under 17.
   - Meanwhile, the rating with the smallest number of content titles are NC-17 (no children under 17 admitted) and UR(unrated).

5. What is the most common rating for Netflix movies and TV shows?
   - The rating with the highest number of movies is TV-MA with 6126 titles.
   - The rating with the highest number of TV shows is TV-MA with 2664 titles.

6. Which are the top 10 content producing countries?
   - The highest number of titles available on Netflix is the United States, with 2809 titles. India has the second-highest number of titles with 972, while the United Kingdom has 418 titles. Japan, South Korea, Canada, Spain, France, Mexico, and Egypt round out the remaining countries on the top 10 list.

7. Which directors or actors/actresses appear most frequently on Netflix?
   - The first position belongs to Rajiv Chilaka, an Indian director who has managed 19 content titles at Netflix.
   - The first position belongs to Shah Rukh Khan, an Indian actor who has appeared in 43 content titles on Netflix.


 















