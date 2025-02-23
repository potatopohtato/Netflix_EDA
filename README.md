# Netflix Business Case Analysis

## Overview

This repository contains a Jupyter Notebook (`Netflix_BusinessCase.ipynb`) that performs a comprehensive analysis of Netflix's content dataset. The dataset includes information about various TV shows and movies available on Netflix, such as their titles, directors, cast, countries of origin, release years, ratings, durations, genres, and descriptions. The analysis aims to provide insights into Netflix's content strategy, helping to identify trends and preferences across different regions and time periods.

## Problem Statement

Netflix, as a leading media streaming platform, seeks to identify the types of shows and movies that will appeal to audiences across different countries, enabling continued global growth. The analysis focuses on answering the following key questions:

1. **What type of content is available in different countries?**
2. **How has the number of movies released per year changed over the last 20-30 years?**
3. **What is the comparison between TV shows and movies?**
4. **What is the best time to launch a TV show?**
5. **Which actors and directors are associated with different types of shows and movies?**
6. **Has Netflix shifted its focus toward TV shows more than movies in recent years?**

By addressing these questions, the analysis aims to develop insights that will help Netflix decide the types of content to produce and refine strategies to grow its business across various countries.

## Dataset

The dataset used in this analysis is named `Netflix_Case.csv` and contains 8807 rows and 12 columns. The columns include:

- `show_id`: Unique ID for each show/movie.
- `type`: Type of content (Movie or TV Show).
- `title`: Title of the show/movie.
- `director`: Director of the show/movie.
- `cast`: Main cast members.
- `country`: Country of origin.
- `date_added`: Date the show/movie was added to Netflix.
- `release_year`: Year the show/movie was released.
- `rating`: Content rating (e.g., PG-13, TV-MA).
- `duration`: Duration of the content (in minutes for movies, seasons for TV shows).
- `listed_in`: Genre(s) of the content.
- `description`: Brief description of the content.

## Key Steps in the Analysis

1. **Data Loading and Initial Exploration**:
   - The dataset is loaded and basic information about the dataset is explored, including the shape, data types, and missing values.

2. **Data Cleaning**:
   - Missing values are handled, and incorrect data entries are corrected.
   - The `date_added` column is converted to a datetime format for easier analysis.
   - New columns (`year_added` and `month_added`) are created to analyze the time when content was added to Netflix.

3. **Data Exploration and Non-Graphical Analysis**:
   - The dataset is split into two categories: Movies and TV Shows.
   - The duration of movies and TV shows is standardized (minutes for movies, seasons for TV shows).
   - The oldest and most recent content on Netflix is identified.

4. **Graphical Analysis**:
   - Visualizations are created to explore trends in content release over time, the distribution of content types, and the popularity of different genres.

5. **Insights and Recommendations**:
   - Based on the analysis, insights are drawn to help Netflix make data-driven decisions about content production and distribution.

## Key Findings

- **Content Types**: The dataset contains both movies and TV shows, with movies being more prevalent.
- **Release Trends**: The number of movies released per year has increased significantly over the last 20-30 years.
- **Content Duration**: Movies typically range from 90 to 120 minutes, while TV shows usually have 1 to 5 seasons.
- **Popular Genres**: Dramas, comedies, and international movies are among the most popular genres on Netflix.
- **Content Addition**: The majority of content is added to Netflix in the months of January and December.

## How to Use This Repository

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/netflix-business-case.git
   ```

2. **Install Dependencies**:
   Ensure you have the required Python libraries installed. You can install them using:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. **Run the Jupyter Notebook**:
   Open the `Netflix_BusinessCase.ipynb` notebook in Jupyter and run the cells to perform the analysis.

4. **Explore the Results**:
   The notebook contains detailed explanations and visualizations that provide insights into Netflix's content strategy.

## Conclusion

This analysis provides valuable insights into Netflix's content library, helping to identify trends and preferences across different regions and time periods. By leveraging these insights, Netflix can make informed decisions about content production and distribution, ultimately driving global growth and audience engagement.

## Author

- **Pranav P**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback and contributions are highly appreciated!
