# Disney+ Content Exploratory Data Analysis (EDA)

## Project Description
This project performs an Exploratory Data Analysis (EDA) on the Disney+ content catalog. The goal is to understand the characteristics of movies and TV shows available on the platform, including release trends, content types, ratings, genres, and more.

## Objective
To uncover insights into the Disney+ content library, identify patterns in content acquisition and production, and visualize key distributions.

## Data Source
The primary dataset used is `disney_plus_titles.csv`, sourced from Kaggle.

## Tools and Technologies
* **Python**
* **Jupyter Notebook**
* **Pandas** for data manipulation and analysis
* **Matplotlib** and **Seaborn** for data visualization

## Key Findings
* **Content Split:** The majority of titles on Disney+ are Movies, significantly outnumbering TV Shows.
* **Temporal Trends:** There's a clear surge in content added around the launch of Disney+ (late 2019) and in subsequent years.
* **Ratings:** The platform predominantly features family-friendly ratings such as TV-G, G, TV-PG, and PG.
* **Genres:** "Family," "Comedy," and "Animation" are among the most common genres.
* **Movie Duration:** Average movie duration varies by rating, with G and TV-G content often being shorter than PG or PG-13, and outliers indicating unusually long movies.

## How to Run the Notebook
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/bindugayathri/DisneyPlus_EDA.git](https://github.com/bindugayathri/DisneyPlus_EDA.git)
    ```
2.  **Navigate to the Project Directory:**
    ```bash
    cd DisneyPlus_EDA
    ```
3.  **Install Dependencies:** (It's recommended to use a virtual environment, but for simplicity, you can install globally if you prefer)
    ```bash
    pip install pandas matplotlib seaborn
    ```
4.  **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook DisneyPlus_Analysis.ipynb
    ```

## Future Work
* **Recommendation System Development:** Explore building a content recommendation system based on genres, content features, or hypothetical user preferences.
* **External Data Integration:** Combine this dataset with external data sources, such as critic reviews, audience scores (e.g., IMDb, Rotten Tomatoes), or streaming performance data, to gain richer insights.
* **Advanced Text Analysis:** Conduct more sophisticated Natural Language Processing (NLP) on movie/TV show descriptions, including topic modeling or entity extraction, to identify common themes or concepts.
* **Time-Series Forecasting:** If new content addition rates or trends are a focus, consider time-series forecasting to predict future content growth.
* **Interactive Dashboard:** Create an interactive dashboard (e.g., using Dash, Streamlit, or Tableau) to allow users to explore the data dynamically.

## Author
[Bindu Gayathri](https://github.com/bindugayathri)
