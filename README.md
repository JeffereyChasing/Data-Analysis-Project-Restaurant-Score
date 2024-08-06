# Foundation of Data Science Project

This project analyzes data from Ubereats restaurants to explore various insights and answer specific research questions. The dataset is sourced from Kaggle and includes detailed information about restaurants and their menus.

## Datasets Overview

### restaurants.csv
[Dataset origin](https://kaggle.com/datasets/ahmedshahriarsakib/uber-eats-usa-restaurants-menus/data)

This sub-dataset includes a total of 11 columns of different information about restaurants on Ubereats. The full column names are:
- `id`: Restaurant id
- `position`: Restaurant position in the search result
- `name`: Restaurant name
- `score`: Restaurant score
- `ratings`: Ratings count
- `category`: Restaurant category
- `price_range`: Price range of the restaurant
- `full_address`: Restaurant full address
- `zip_code`: Zip code
- `lat`: Latitude
- `long`: Longitude
- `locality`: Indicates whether the restaurant serves American cuisine (added column)
- `menu_diversity`: Based on restaurant-menus dataset (added column)

### restaurant-menus.csv
This sub-dataset contains information about restaurants' menus. There are 5 columns in this sub-dataset:
- `restaurant_id`: Restaurant id
- `category`: Menu category
- `name`: Menu Name
- `description`: Menu description
- `price`: Menu price

## Research Question
What is the total and direct effect of locality on the restaurant score?

## Project Structure
The project is structured into various sections as follows:

1. **Data Loading and Cleaning**: This section includes the code to load and clean the datasets to prepare them for analysis.
2. **Exploratory Data Analysis (EDA)**: This section explores the datasets to find initial insights and patterns.
3. **Statistical Analysis**: This section conducts statistical analysis to answer the research question.
4. **Results and Discussion**: This section presents the results of the analysis and discusses the findings.

## How to Run the Project
1. Clone the repository to your local machine.
2. Ensure you have the necessary dependencies installed. You can install them using the following command:
   ```bash
   pip install -r requirements.txt
