# NoSQL Challenge

This repository contains the solution to the NoSQL Challenge, which involves working with MongoDB to perform data manipulation, exploration, and analysis tasks.

## Part 1: Database and Jupyter Notebook Set Up

- Imported data from the `establishments.json` file into a MongoDB database named `uk_food`.
- Set up a Jupyter Notebook (`NoSQL_setup.ipynb`) to interact with the MongoDB database.
- Confirmed the creation of the database and loaded data properly.
- Reviewed the collections and documents within the database.
- Updated the database with new documents and performed data type conversions.

## Part 2: Update the Database

- Added a new restaurant ("Penang Flavours") to the establishments collection.
- Updated the new restaurant with the correct BusinessTypeID.
- Deleted documents where the LocalAuthorityName is "Dover".
- Updated data types for longitude, latitude, and RatingValue fields.

## Part 3: Exploratory Analysis

- Explored the dataset to answer specific questions provided by the client, Eat Safe, Love.
- Utilized MongoDB queries and aggregation pipelines to extract insights from the data.
- Answered questions such as identifying establishments with a hygiene score of 0, establishments with a high rating in London, and top-rated establishments near a new restaurant.

## Conclusion

The provided Jupyter Notebook files (`NoSQL_setup.ipynb` and `NoSQL_analysis.ipynb`) contain the code and explanations for each part of the challenge. The README file serves as a guide to understanding the tasks performed and the solutions provided.

For more details, refer to the Jupyter Notebook files in this repository.

