# Video Game Dataset
This dataset contains information about video games, including their release year, platform, genre, publisher, and sales data in various regions.
## Data Source
The data was collected from kaggle website.

## Data Description

The dataset contains 16 columns and approximately 16446 rows. Each row represents a single video game and includes information such as the game's title, release year, platform, genre, publisher, and sales data in North America, Europe, Japan, and other regions.

The columns in the dataset are as follows:
- Name: The name of the game
- Platform: The console/platform on which the game was released
- Year_of_Release: The year the game was released
- Genre: The genre of the game
- Publisher: The publisher of the game
- NA_Sales: Sales data for North America (in millions)
- EU_Sales: Sales data for Europe (in millions)
- JP_Sales: Sales data for Japan (in millions)
- Other_Sales: Sales data for other regions (in millions)
- Global_Sales: Total worldwide sales (in millions)
- Critic_Score: Aggregate score compiled by Metacritic staff
- Critic_Count: The number of critics used in coming up with the Critic_score
- User_Score: Score by Metacritic's subscribers
- User_Count: Number of users who gave the user_score
- Developer: Party responsible for creating the game
- Rating : Rating given to the game

## Data Preprocessing
The dataset required some preprocessing before it could be used for analysis. This included filling missing values with appropriate values, converting some columns to the correct data type, and dropping some unnecessary columns.
For this dataset 6 columns were dropped. The features dropped are from Critic_Score to Rating as most of the values in those features were missing.

