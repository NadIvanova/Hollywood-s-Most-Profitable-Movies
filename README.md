# Hollywood's Most Profitable Movies
The goal of this project is to analyze the performance of Hollywood movies, focusing on a dataset of films released between 2007 and 2012. I intend to explore various attributes that may influence a movie's success, such as title, genre, production studio, profitability, and ratings.

## Data Source
The data used in this analysis comes from [InformationIsBeautiful.net](https://public.tableau.com/app/sample-data/HollywoodsMostProfitableStories.csv). This dataset includes information on the title, genre, studio, profitability, and ratings of the movies.

## Analysis Tools

To conduct this analysis, data cleaning and interactive dashboards have been developed using the following tools:

- **RStudio:** RStudio is a must-know tool for everyone who works with the R programming language. It was used in the project for data analysis to import, access, transform, explore, and plot the data.
- **Power BI:** An interactive dashboard to visualize and explore the different aspects of movie performance.

## Methodology

The methodology for this analysis involved both initial data exploration and cleaning steps to ensure data quality and integrity. The process is outlined as follows:

### Data Cleaning and Exploration

1. **Initial Data Exploration:**
   - Utilized R libraries `tidyverse` and `dplyr` for data manipulation.
   - Loaded the dataset and performed initial exploratory analysis to understand data structure and content.

2. **Data Quality Checks:**
   - Examined the dataset for missing values, unique distributions of categorical variables, and summary statistics to get an initial understanding of the data.

3. **Cleaning Steps:**
   - Identified and removed rows with missing values to ensure the analysis is based on complete cases only.
   - Used `summary` to review the dataset post-cleaning, ensuring that the cleaning process preserved the integrity of the data.

4. **Exploratory Data Analysis Visualisation in RStudio:**
    - A scatterplot example was created and it depicted the number of Rotten Tomatoes received by each Lead Hollywood Studio from 2007 to 2012.
    - The second example presents data analysis by a bar chart, as shown below.
![Scatterplot Hollywood](https://github.com/NadIvanova/Hollywood-s-Most-Profitable-Movies/assets/29489913/9f85dd21-ba36-487f-a5c2-2058442c12dc)

![Barplot Hollywood](https://github.com/NadIvanova/Hollywood-s-Most-Profitable-Movies/assets/29489913/4c281b25-3dba-472b-94d5-ef7c3b8dedff)


### Power BI Processing

- In Power BI, used the Power Query Editor to further clean the data by removing a row with an empty value, aligning the dataset for accurate analysis.

This comprehensive approach to data preparation set the stage for insightful analysis conducted through interactive dashboards in Power BI, enabling a deep dive into the performance metrics of Hollywood movies. 
One of the requirements for the dashboard was that the company would like us to use their brand colors, which are blue, green, and brown (light or dark shades of each color were also acceptable). This requirement was closely followed to finalise the dashboard.

## Key Findings

A brief overview of the most interesting insights obtained from the analysis, all shown on the dashboard:
- The average Rotten Tomatoes ratings of each genre
- The number of movies produced per year
- The audience score for each film
- The profitability per studio
- The worldwide gross per genre
- TOP 5 most profitable films.

### Power BI Dashboard
![Hollywood Movies](https://github.com/NadIvanova/Hollywood-s-Most-Profitable-Movies/assets/29489913/f374f3ef-b245-446a-b3eb-3365e2cf6831)

