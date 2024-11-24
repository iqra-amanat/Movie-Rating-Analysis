# Movie Rating Analysis
### IMDb Top 1000 Movies Analysis

This project analyzes the IMDb Top 1000 movies dataset to uncover insights about movie ratings, genres, revenues, and trends over the years. It involves data cleaning, exploratory data analysis (EDA), and visualizations to explore key relationships and patterns.


---

### 📂Dataset Description

The dataset contains information about the top 1000 movies on IMDb, including:

Series_Title: Title of the movie.

Released_Year: Year the movie was released.

IMDB_Rating: IMDb rating of the movie.

Genre: Genre of the movie.

Meta_score: Metascore rating.

Director: Director of the movie.

No_of_Votes: Number of votes the movie received.

Gross: Total gross revenue of the movie.



---

### 📋 Project Workflow

### 1. Data Cleaning

Converted columns such as Gross and Meta_score to numeric for accurate analysis.

Handled missing values in key columns such as Gross to ensure the dataset was ready for analysis.


### 2. Exploratory Data Analysis (EDA)

Identified top-rated movies based on IMDb ratings.

Analyzed the distribution of movie genres.

Explored yearly trends in average IMDb ratings.

Investigated the relationship between:

Number of votes and IMDb ratings.

Metascore ratings and IMDb ratings.


Analyzed total gross revenue by genre.

Highlighted the top 10 grossing movies.


### 3. Visualizations

Bar charts for genre distribution and total gross revenue by genre.

Line chart for yearly average IMDb ratings.

Scatter plots for:

Votes vs IMDb ratings.

Meta score vs IMDb ratings.




---

### 🔑Key Insights

1. Top-Rated Movies: Identified the top 10 movies with the highest IMDb ratings, along with their directors.


2. Popular Genres: Highlighted the most common movie genres and their frequency.


3. Yearly Trends: Observed how average IMDb ratings have changed over the years.


4. Revenue Insights: Determined which genres generated the highest gross revenue.


### 5. Correlation:

A positive correlation between the number of votes and IMDb ratings.

An observable relationship between meta scores and IMDb ratings.





---

### Technologies Used

Python: For data manipulation and analysis.

Pandas: For data cleaning and transformations.

Matplotlib: For creating visualizations.

Seaborn: For advanced data visualization.



---

### 🚀How to Run the Project

1. Clone the repository:

git clone <repository-link>


2. Install the required libraries:

### 🛠️pip install pandas matplotlib seaborn


3. Download and place the dataset (imdb_top_1000.csv) in the working directory.


4. Run the Python script or Jupyter Notebook to execute the analysis and generate visualizations.




---

### Sample Visualizations

Add sample visualizations in your README using the following format after uploading image files:

![Genre Distribution](path/to/genre_distribution.png)
![Yearly Average IMDb Ratings](path/to/yearly_avg_ratings.png)




