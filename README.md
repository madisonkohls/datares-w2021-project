# Project Title
This project is a part of the [Data Blog](https://datares.github.io/#/datablog) at [DataResolutions](https://datares.github.io/#/).  The article published on this project, along with other articles from Data Blog, can be found on [Medium](https://medium.com/@ucladatares).

## Project Motivation/Description
The purpose of this project is to explore trends among over 40,000 feature films released on or before July 2017. Our team specifically wanted to use this metainformation on movies to find possible correlations between budget, revenue, production company, and rating, as well as explore trends in genres, keywords, and production countries.

### Technologies Used
* Python (Pandas, NumPy, Matplotlib, Seaborn)

## Getting Started

1. Clone this repository (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here]() within this repo.  
3. Data processing/visualization scripts are being kept [here]()

## Data 
Our dataset is [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset) from Kaggle. It has over 45,000 entries of metainformation on Movies released before and on July 2017.

## Data Cleaning
For the data cleaning process, the only csv file that had missing/nonsensical values was the movies_metadata.csv file. To clean the data, we first removed all films that did not have a title and then also removed all film that had a runtime of less than 40 minutes (for the purpose of our EDA we wanted to look at movies that followed the [definiton of being a feature film](https://en.wikipedia.org/wiki/Feature_film)). The notebook where we cleaned the the data can be found (here)[].

## Data Analysis
For our data analysis, we looked into a few key questions:
### 1) What are some keywords in various genres?
The notebook can be found (here)[].

## Contributing DataRes Members

|Name     | Position | GitHub Handle   | 
|---------|----------|----------------|
|Madison Kohls | Team Lead | [@madisonkohls](https://github.com/madisonkohls) |
|Bonnie Liu | Member | [@bonnieliu2002](https://github.com/bonnieliu2002) |
|Isha Shah | Member | [@ishashah146](https://github.com/ishashah146) |
|Polina Pranovich | Member | [@polinapra](https://github.com/polinapra) |
|Danielle Goldwirth | Member | [@danigold1020](https://github.com/danigold1020) |
