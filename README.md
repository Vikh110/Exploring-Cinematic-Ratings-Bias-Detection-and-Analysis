# Exploring Film Ratings: Bias Detection and Analysis

## Project Overview

This project explores and analyzes movie ratings from various platforms, focusing on detecting potential biases in Fandango's ratings in 2015.
 
## Data Source:

https://github.com/fivethirtyeight/data.

The dataset includes two CSV files: one detailing Fandango’s Star and Displayed Ratings, and another aggregating movie ratings from other platforms such as Metacritic, IMDB, and Rotten Tomatoes.

all_sites_scores.csv contains every film that has a Rotten Tomatoes rating, a RT User rating, a Metacritic score, a Metacritic User score, and IMDb score,and at least 30 fan reviews on Fandango. 
The data from Fandango was pulled on Aug. 24, 2015.

fandango_scrape.csv contains every film 538 pulled from Fandango.

The analysis examines whether Fandango's ratings were skewed towards more favorable outcomes, potentially influencing ticket sales.

## Key Objectives

- **Exploratory Analysis:** Identify patterns, trends, and outliers in the movie ratings data.
- **Cross-Platform Comparison:** Compare Fandango’s ratings with those from other platforms like Rotten Tomatoes, Metacritic, and IMDb to spot discrepancies.
- **Visualization:** Use charts and graphs to effectively communicate findings.
- **Bias Investigation:** Explore the potential extent of bias in Fandango's ratings using data-driven techniques.

## Tools and Libraries Used

- **Python:** The primary programming language used for this analysis.
- **Pandas:** For data manipulation, cleaning, and preprocessing.
- **Matplotlib:** For creating static, animated, and interactive visualizations.
- **Seaborn:** For statistical data visualization, used to plot complex graphs with less code.
- **NumPy:** For numerical computations and array manipulation.

## Project Structure

- **`fandango_final.ipynb`:** The main Jupyter Notebook containing all the code, analysis, and visualizations.

## Results and Insights

**Bias Detection**: The analysis revealed that Fandango's ratings were indeed biased towards higher ratings compared to other platforms. This bias could potentially be linked to efforts to drive higher ticket sales.

**Comparative Analysis**: Significant discrepancies were found between Fandango's ratings and those from Rotten Tomatoes, Metacritic, and IMDb, suggesting that consumers might need to be cautious when relying solely on Fandango's ratings.
