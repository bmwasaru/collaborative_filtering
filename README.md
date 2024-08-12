# Collaborative Filtering

Technique used in recommendations systems to predict preferences of a user by collecting preferences from many users.

There are 2 types:
1. user based collaborative filtering - finds users who are similar to the target user based on their past interactions (e.g., ratings or purchases) and recommends items that these similar users liked
2. item based collaborative filtering - looks at the similarity between items based on users' past behavior. It recommends items that are similar to what the target user has liked in the past

The notebook looks at how to implement these types of filtering.

## To get started

Clone the repo then:

```$ pip install -r requirements.txt```

The run jupyter notebook

```$ jupyter notebook collaborative_filtering.ipynb```