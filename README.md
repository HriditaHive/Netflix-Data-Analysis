# Netflix-Data-Analysis
This project focuses on performing an exploratory data analysis (EDA) on a Netflix dataset to uncover insights about the content like trends, genre distribution and regional patterns. By leveraging visualizations and statistical methods, this project aims to provide actionable insights that could aid in content strategy, audience targeting, and better understanding of the Netflix catalog. The analysis is carried out in Jupyter Notebook using Python 3, leveraging the capabilities of the pandas and seaborn libraries.

## Objectives
The main goals of this project are to:        
- Explore data attributes such as title, release year, type, genre, and duration.
- Perform Exploratory Data Analysis (EDA) on the dataset to uncover key insights.
- Analyze correlations between variables.
- Draw insights that could assist in content recommendation and personalization.

## Data Source
This Netflix Dataset has information about the TV Shows and Movies available on Netflix till 2021.       
This dataset is collected from Flixable which is a third-party Netflix search engine, and available on Kaggle website for free.    
It has been provided in this repository as **_Netflix Dataset.csv_** for ease of use.      
The dataset includes information on Netflix’s catalog, such as titles, genres, release dates, country of origin, and content type (Movies or TV Shows). The data allows us to analyze different dimensions of Netflix's library and see how certain aspects have changed over time. 

## Project Structure
The main sections of this project include:
- Data Preprocessing: Handling duplicate values and transforming data to prepare it for analysis.
- Exploratory Data Analysis (EDA): Visualizations and statistical summaries to explore key insights and trends.
- Insight Generation: Key findings based on the analysis.
- Conclusion and Recommendations: Suggestions based on the identified patterns.

## Getting Started
To replicate this analysis, ensure you have Python 3.x installed along with the following libraries:  

``` 
pip install pandas matplotlib seaborn
```    

To clone the project:      
```
git clone <repository-url>
cd Netflix-Data-Analysis
```

## Analysis Process
1. **Import the Dataset**
2. **Explore basic information about the dataset like shape, size and data types.**
3. **Preprocess the data to check for null values, duplicate values and remove them.**
4. **Perform Exploratory Data Analysis through a series of questions such as:**
   - For 'Zozo', show the Show ID, Director and other details of the show.
   - With the help of a Bar Graph, find the year in which the most TV shows and Movies were released.
   - Show the number of movies and tv shows in the data set with a count plot.
   - Show all the movies released in a particular year (eg. 2017).
   - Show the Titles of all the TV Shows released in India (or any other specific country).
   - Show top 10 directors who gave the highest number of TV shows and movies to Netflix.
   - Show all the Records where "Category is Movie and Type is Comedies" or "Country is United States"
   - In how many movies/shows was Tom Cruise cast?
   - What are the different ratings defined by Netflix? How many movies got the 'TV-14' rating in Canada? How many TV Shows got the 'R' rating after year 2018?
   - What is the maximum duration of a movie on Netflix?
   - Which individual country has the highest no. of TV Shows?
   - Sort the dataset by Year, showing the latest movies first.
   - Show records where Category is 'Movie' and Type is 'Dramas' OR Category is 'TV Show' & Type is 'Kids' TV'.
  
  
## Key Insights
- **Content Growth Over Time:** Netflix’s content catalog has grown significantly, with an increasing number of movies and TV shows released annually. There has been a noticeable increase in Netflix Originals, which has contributed to this growth.         
- **Movies vs. TV Shows:** Movies make up a larger portion of the Netflix catalog compared to TV shows. However, the growth rate of TV shows has been increasing steadily, hinting at Netflix's focus on producing episodic content.       
- **Genre Popularity:** Dramas, comedies, and documentaries are among the most popular genres on Netflix. This is consistent with global viewing trends, where viewers often prefer engaging, story-driven genres.       
- **Regional Content Distribution:** A significant portion of Netflix's content originates from the United States, followed by India, the United Kingdom, and other countries. This demonstrates Netflix's focus on producing content that resonates with audiences worldwide.        
- **Content Ratings:** Netflix offers content with a wide variety of ratings, catering to different audience demographics. Ratings such as PG-13 and TV-MA are prevalent, reflecting Netflix's appeal to both younger and older audiences.

## Visualization Highlights
- **Growth of Netflix Catalog Over Time:** This bar chart shows the yearly addition of new titles, indicating the steady increase in content, particularly since 2015.
- **Content Type Comparison (Movies vs. TV Shows):** A bar chart depicts the numbers of movies and TV shows, emphasizing the dominance of movies in Netflix's catalog.

## Conclusion and Recommendations
The Netflix catalog has evolved substantially, growing not only in volume but in diversity of genres and content types. While movies still dominate, the increasing number of TV shows suggests a shift in Netflix’s content strategy. Additionally, regional content distribution highlights Netflix’s global reach, although a significant amount of content remains U.S.-centric. This analysis can guide Netflix in strategic content investments, aligning with viewer preferences and expanding their global market.       The following recommendations are proposed:       
- Content Strategy: Netflix could focus on producing more original content in popular genres.
- Regional Insights: Expanding region-specific content for diverse audience engagement.
- Personalization: Utilize findings on ratings and genres to refine recommendation algorithms.

## Future Work
Future improvements to this project could include:        
- **Sentiment Analysis:** Analyzing reviews or comments for deeper insights.
- **Recommendation Engine:** Building a content-based recommendation system based on insights.
- **Predictive Analysis:** Forecasting future content trends using historical data.

## Repository Content
- The Jupyter notebook for analysis (Netflix-Data-Analysis.ipynb)
- The dataset used for analysis (Netflix Dataset.csv)

## Acknowledgments
Thanks to Kaggle for providing the dataset. This project is part of a broader effort to understand media consumption patterns and improve content curation for diverse audiences.
