
# UK Food Standards Agency Data Analysis

## Background
The UK Food Standards Agency evaluates establishments across the United Kingdom and provides food hygiene ratings. This project involves analyzing the ratings data to assist the editors of a food magazine, Eat Safe, Love, in deciding where to focus future articles.

## Part 1: Database and Jupyter Notebook Set Up
1. Import the establishments data provided in the establishments.json file and load it into a MongoDB database named uk_food.
2. Confirm that the database and collection were created properly and display one document from the establishments collection.

## Part 2: Update the Database
1. Add information for a new halal restaurant in Greenwich to the database.
2. Find and update the BusinessTypeID for "Restaurant/Cafe/Canteen".
3. Remove establishments within the Dover Local Authority from the database.
4. Convert certain number values stored as strings to numeric types.

## Part 3: Exploratory Analysis
1. Answer specific questions about the dataset to help Eat Safe, Love magazine in their decision-making process:
    - Which establishments have a hygiene score equal to 20?
    - Which establishments in London have a RatingValue greater than or equal to 4?
    - What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
    - How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

## Conclusion
By completing this analysis, valuable insights will be provided to Eat Safe, Love magazine, enabling them to make informed decisions about where to focus future articles and reviews.
