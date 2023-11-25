# UK_Food_Hygiene_Ratings_Database_Evaluation

Overview:
The project aims to assist the editors of "Eat Safe, Love" magazine in evaluating UK food hygiene ratings. The Food Standards Agency assesses various establishments nationwide, providing hygiene ratings. This project involves analyzing and manipulating the ratings data to aid journalists and food critics in deciding where to focus their future articles.

Programs used:
    * Python
    * MongoDB
    * Jupyter Lab
    
Part 1: Database and Jupyter Notebook Setup:
    1. Import establishments.json data into MongoDB.
    2. Import necessary libraries (PyMongo, Pretty Print).
    3. Create a Mongo Client instance.
    4. Confirm database creation, data loading, and access a sample document.
    
Part 2: Database Update:
    1. Add a new unrated halal restaurant in Greenwich to the database.
    2. Find and update BusinessTypeID for "Restaurant/Cafe/Canteen".
    3. Remove establishments within the Dover Local Authority.
    4. Convert certain string values to numbers (latitude, longitude, RatingValue).
    
Part 3: Exploratory Analysis: Explore specific questions provided by "Eat Safe, Love" for insights.
        * Identify establishments with a hygiene score of 20.
        * Filter establishments in London with RatingValue greater then or equal to 4.
        * Determine the top 5 establishments with RatingValue of 5, sorted by lowest hygiene score near "Penang 
          Flavours".
        * Count establishments with hygiene score 0 in each Local Authority area (sorted from highest to
          lowest).