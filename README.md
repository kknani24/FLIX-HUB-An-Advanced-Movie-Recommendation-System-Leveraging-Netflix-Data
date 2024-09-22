#  FLIX-HUB: An Advanced Movie Recommendation System Leveraging Netflix Data

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-%23F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)


<div align="center">
  <img src="https://media.tenor.com/NerN41mjgV0AAAAC/netflix-intro.gif" alt="Netflix Intro Animation">
</div>

## Table of Contents
- [Recommendation System (FLIX-HUB)](#recommendation-system-flix-hub)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Data Preprocessing](#data-preprocessing)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Feature Engineering](#feature-engineering)
  - [Recommendation System](#recommendation-system)
  - [Results](#results)
  - [Contributing](#contributing)
  - [License](#license)

## Project Overview

This project performs a comprehensive analysis of Netflix data and implements a content-based recommendation system called FLIX-HUB. It includes data preprocessing, exploratory data analysis, advanced feature engineering, and a movie/TV show recommendation engine.

## Features

- Data cleaning and preprocessing
- Exploratory data analysis with interactive visualizations
- Text processing and feature engineering
- Content-based recommendation system
- Support for both movies and TV shows

## Installation

To run this project, you need to have Python installed on your system. Then, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Recommendation-System .git
   ```

2. Navigate to the project directory:
   ```
   cd movie-recommendation-system.ipynb
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

To use the FLIX-HUB recommendation system:

1. Run the Jupyter notebook or Python script.
2. Use the `FlixHub` class to get recommendations:

```python
flix_hub = FlixHub(final_data, cosine_sim)
movies, tv_shows = flix_hub.recommendation('Movie Title', total_result=10, threshold=0.5)

print('Similar Movie(s) list:')
for movie in movies:
    print(movie)

print('\nSimilar TV_show(s) list:')
for tv_show in tv_shows:
    print(tv_show)
```

## Data Preprocessing

The data preprocessing steps include:
- Loading the Netflix dataset
- Handling missing values
- Cleaning text data (titles, descriptions, etc.)
- Creating a bag of words representation

## Exploratory Data Analysis

The EDA process includes various visualizations:
- Distribution of content types (movies vs. TV shows)
- Number of movies released each year
- Top countries producing Netflix content
- Movie ratings distribution
- Word clouds for titles, descriptions, and genres

## Feature Engineering

Advanced feature engineering techniques are applied:
- Text cleaning and normalization
- TF-IDF vectorization
- Cosine similarity calculation

## Recommendation System

The FLIX-HUB recommendation system uses:
- Content-based filtering
- Cosine similarity for finding similar content
- Separate recommendations for movies and TV shows

## Results

The project provides insights into Netflix's content library and offers personalized recommendations based on user input. Some key findings include:
- Distribution of movies vs. TV shows
- Trends in content production over the years
- Popular genres and themes

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
