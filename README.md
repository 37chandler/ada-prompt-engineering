# Prompt Engineering

This assignment requires you to use prompt engineering to improve classification performance 
of a ChatGPT model. This assignments mimics work done as part of a Forestry MS project by 
Madeline Damon. Part of her work was understanding the types of authors who were publishing
in different fields. Part of _that_ is classifying academic articles into groups, a form
of classification modeling.

The folder `data/` includes the file `training-data.csv` that holds the data you'll use for this assignment. In that file you will find about 1000 abstracts, along with categories determined by Madeline and myself. Your goal is to refine a series of ChatGPT prompts that give the most accurate classifications. 

Note: the categories in that file


Find some basic version of this?
Clean up Madeline’s “Davinci training set” data so it has a reasonable number of categories. Give them an extract of 1000 extra ones.
Give them code to estimate the costs of what they’re doing.
Give them a notebook like “AI Training Set.ipynb” that gives them categories and basic prompt. “Please categorize this abstract:…”. Their goal is to get it to return categories. At each modification, run this against 100 random abstracts and get the accuracy. (Maybe do it by category for them?)
Write up your experience and the best performing prompt. Report costs to score 1000 abstracts.