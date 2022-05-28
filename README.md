# <u>Data Scientist nanodegree / Udacity project : Recommendations with IBM</u>
## Table of Contents
1. [Project info](#project-info)
2. [Repository files info](#repository-files-info)

***

### Project info

The purpose of this project is to analyse the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will like. 

The deliverable of the project is a notebook where the following task will be performed:

I. Exploratory Data Analysis

II. Rank Based Recommendations which identify the most popular articles simply based on the most interactions they have.

III. Collaborative Filtering recommendations which are based on similar users in terms of the items they have interacted with. 

V. Matrix Factorization machine learning approach to building recommendations. Using the user-item interactions, I build out a matrix decomposition and get an idea of how well we can predict new articles an individual might interact with.


***
### Repository files info:


* `data/articles_community.csv` contains the details of the articles..
* `data/user-item-interactions.csv` contains the of the users with the articles.
* `project_tests.py` contains the library used in the notebook to check results.
* `Recommendations_with_IBM.ipynb`  is the notebook containing the tasks described above.
* `user_item_matrix.p` is the pickle file containing the user_ids items matrix.


