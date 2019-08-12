# Mod-3-Project

## Classifying Price of Steam Games by Kevin Zhao and Rene Ventura

The main experiment is laid out in Final Presentation.ipynb. We have an overview of the experiment, step by step details
on how we ran the experiment, and the results of our experiment and next steps. You can also take a look at data_getter.py 
and model_funcs.py to see more details of the functions we used to complete the experiment. 

This project was to classify price of games that are present on the Steam platform. As most games on the platform are indie games, the prices may vary depending on the genre, tags, whether it has coop or the amount of reviews it has. The whole Steam library at the time was taken from the store API with a function we created. Due to the large volume of games (around 76k), it was split into parts with each part being processed as soon as obtained through our functions that makes it a dataframe and cleans the data. The resulting dataset is the data that has been cleaned and corrected if needed. 

From there PCA was ran to determine the amount of variance that is explained by the features we choose and used those values in our models. Models ran included decision tree, random forest, and support vector machines. 
