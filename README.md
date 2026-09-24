A simple **Popularity-Based Recommender System** implemented with Python.

The project identifies popular restaurants based on the **number of ratings** they have received. The most-rated restaurants are then matched with their cuisine information.

## Project Overview

The goal of this project is to explore a simple recommendation approach based on overall item popularity.

Unlike personalized recommendation systems, this approach does not make recommendations based on an individual user's preferences. Instead, it identifies restaurants that have received a higher number of ratings from users.

## Libraries

* **Pandas**
* **NumPy**

## Dataset

The project uses two CSV files:

* `rating_final.csv` — restaurant rating data
* `chefmozcuisine.csv` — restaurant cuisine information

## Method

The recommendation process includes the following steps:

1. Load the restaurant rating data.
2. Count the number of ratings for each restaurant using `placeID`.
3. Sort restaurants based on the number of ratings.
4. Identify the most-rated restaurants.
5. Match the selected restaurants with their cuisine information.

## Example

The project identifies the following restaurants among the most-rated places:

* 135085
* 132825
* 135032
* 135052
* 132834

Their cuisine information is then retrieved from `chefmozcuisine.csv`.

## Project Structure

```text
PopularityRecommenderSystem/
│
├── README.md
├── PopularityRecommenderSystem.py
│
└── data/
    ├── rating_final.csv
    └── chefmozcuisine.csv
```

## Purpose

This project was created as a practical exercise to understand the basic concept of **Popularity-Based Recommendation** and its implementation using Python, Pandas, and NumPy.
