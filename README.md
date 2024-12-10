# Recipe-Recommender-Assignment-EDA
# Recipe-Recommender-Assignment-EDA
## Problem Statement

In this project, we will utilize PySpark, a distributed computing framework for processing large-scale data, to build a recommendation system. The PySpark implementation will be deployed on AWS (Amazon Web Services) using EMR (Elastic MapReduce) instances, which provide a scalable and cost-effective way to process large datasets. We will also use s3, an object storage service provided by AWS, to store and retrieve data. By leveraging these technologies, we can efficiently handle the data and compute resources required to build an effective recommendation system.

As an ML engineer at food.com, your responsibility is to develop a recommendation system to suggest recipes to users based on their preferences and the recipes they are currently viewing. The main objective of this recommendation engine is to increase user engagement on the website. By showing users recipes that are relevant to their interests, they are more likely to spend more time exploring the site, which in turn could lead to increased business opportunities, such as collaborations and promotions.

It is essential to understand that the success of this recommendation engine directly impacts the revenue that the recipe site generates. Therefore, designing a high-performing recommender system is crucial to achieve the desired business outcomes.

Creating a recommendation engine from scratch is a complex and time-consuming task. Hence, in this project, you will be required to explore the data and create features that will be utilized to build the recommendation system.

The project will involve working with two CSV files, which are available at the following links:
*	s3a://raw-recipes-clean-upgrad/RAW_recipes_cleaned.csv
-	s3a://raw-interactions-upgrad/RAW_interactions_cleaned.csv

The first file contains all the recipe-related information and will be referred to as Raw_recipes.csv. Each row in this file describes a recipe.

The second file we will be using is the RAW_interactions.csv file. Each row in this data file represents one user reviewing one recipe. Since each user can review multiple recipes, and each recipe can be reviewed by multiple users, there is a many-to-many relationship between users and recipes. However, the combination of user_id and reviewer_id in each row will be unique.

Overall, the project aims to build a recommendation engine that can provide personalized recipe suggestions to users based on their interests and engagement history.

