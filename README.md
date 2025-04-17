# Zomato Exploratory Data Analysis

## Problem Statement

The Zomato exploratory data analysis aims to assist food enthusiasts in discovering the best restaurants and value-for-money options within their locality. It facilitates locating desired cuisines available nearby. 

With a dataset encompassing restaurant details like establishment type, address, city, locality, and cuisine offerings, alongside attributes such as average cost for two, price range, and aggregate ratings, the objective is to uncover insights into restaurant preferences and dining trends. 

Through analyzing factors like average cost, ratings, and customer engagement metrics such as votes and photo counts, this study seeks to provide actionable recommendations for diners seeking satisfying dining experiences.

---

## Data Definition

| Feature               | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **res_id**             | The code given to a restaurant (Categorical)                               |
| **name**               | Name of the restaurant (Categorical)                                       |
| **establishment**      | Represents the type of establishment (Categorical)                         |
| **url**                | The website of the restaurant (Categorical)                                |
| **address**            | The address of the restaurant (Categorical)                                |
| **city**               | City in which the restaurant is located (Categorical)                      |
| **city_id**            | The code given to a city (Categorical)                                     |
| **locality**           | Locality of the restaurant (Categorical)                                   |
| **latitude**           | Latitude of the restaurant (Categorical)                                   |
| **longitude**          | Longitude of the restaurant (Categorical)                                  |
| **zipcode**            | Zipcode of the city in which the restaurant is located (Categorical)       |
| **country_id**         | Country code in which the restaurant is located (Categorical)              |
| **locality_verbose**   | Locality along with the city in which the restaurant is located (Categorical) |
| **cuisines**           | The cuisines a restaurant serves (Categorical)                             |
| **timings**            | The working hours of a restaurant (Categorical)                            |
| **average_cost_for_two** | The average amount expected for 2 people (Numerical)                      |
| **price_range**        | The categories for average cost (Categories - 1, 2, 3, 4) (Categorical)     |
| **currency**           | The currency in which a customer pays (Categorical)                        |
| **highlights**         | The facilities of the restaurant (Categorical)                             |
| **aggregate_rating**   | The overall rating a restaurant has got (Numerical)                        |
| **rating_text**        | Categorized ratings (Categorical)                                          |
| **votes**              | Number of votes received by the restaurant from customers (Numerical)      |
| **photo_count**        | The number of photos of a restaurant (Numerical)                           |
| **opentable_support**  | Restaurant reservation from Opentable (Categorical)                        |
| **delivery**           | Whether the restaurant delivers an order or not (Categorical)              |
| **takeaway**           | Whether the restaurant allows takeaway or not (Categorical)                |
