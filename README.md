# DataScience_Project

# Video Game Sales Analysis

This project analyzes a dataset containing information on video game sales between 1980 and 2016. The dataset includes information on various features such as game titles, genres, platforms, publishers, critic and user scores, and global and regional sales. The objective of this project is to gain insights into the video game industry and trends over the years.

## Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings). It contains 16,446 observations and 16 features, including:

- `Name`: The games' name
- `Platform`: Platform of the games release (i.e. PC, PS4, etc.)
- `Year_of_Release`: Year of the game's release
- `Genre`: Genre of the game
- `Publisher`: Publisher of the game
- `NA_Sales`: Sales in North America (in millions)
- `EU_Sales`: Sales in Europe (in millions)
- `JP_Sales`: Sales in Japan (in millions)
- `Other_Sales`: Sales in the rest of the world (in millions)
- `Global_Sales`: Total worldwide sales (in millions)
- `Critic_Score`: Aggregate score compiled by Metacritic staff
- `Critic_Count`: The number of critics used in coming up with the Critic_score
- `User_Score`: Score by Metacritic's subscribers
- `User_Count`: Number of users who gave the user_score
- `Developer`: Party responsible for creating the game
- `Rating` : Ratings given to the game

After cleaning the data we are left with 10 features and 16412 rows of data. The features from Critic_score to Rating are dropped due to large amount of missing values in them.

## Analysis

The analysis conducted in this project includes:

- Exploratory Data Analysis
- Correlation Matrix
- Trend analysis of various features such as game counts, sales, trend of genre over the years
- Publisher and platform analysis

## Conclusion

From the analysis, we can draw the following conclusions:

- The video game industry has grown significantly over the years, with a spike in sales in the mid-2000s.
- Certain genres, such as Action and Sports, are more popular than others.
- Certain platforms, such as PS2 and X360, have had higher sales than others.
- The most popular video game genres are action, sports, and shooter, while the least popular are strategy, puzzle, and adventure.
-The most successful video game platforms in terms of sales are the PlayStation 2, Xbox 360, and PlayStation 3.
-There is a strong positive correlation between the sales of different regions, indicating that video game sales tend to be similar across different regions.
-Electronic Arts, Activision, and Ubisoft are the top publishers in terms of sales, and they tend to release games on multiple platforms.
-Nintendo is a notable publisher that focuses on its own platforms such as the Wii and the Nintendo DS and has been successful in doing so.
-The top-selling video game of all time is Wii Sports, which was developed and published by Nintendo.
-Compared to other regions the Japanese gaming industry is different.
- The top publishers have released games on a variety of platforms, with Electronic Arts being the top publisher.

## Future Work

This analysis can be expanded by incorporating more features, such as developer information, users age and user reviews, to gain further insights into the video game industry. Additionally, machine learning models can be built to predict game sales and explore further trends.

## Files

- `Video_game_sales_analysis.ipynb`: Jupyter Notebook containing the analysis
- `Video_game_sales.csv`: Dataset used in the analysis
- `README.md`: README file containing information about the project
- `results_pds_project`: Contains overall analysis results
- `Pds video games ppt`: contains the power point presentation

## Dependencies

- Python 3.7 or higher
- pandas
- numpy
- matplotlib
- seaborn

## Instructions

1. Clone the repository to your local machine.
2. Install the dependencies listed above.
3. Open the `video_game_sales_analysis.ipynb` file in Jupyter Notebook.
4. Run each cell in the notebook to reproduce the analysis.
