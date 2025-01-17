# Preferences and consequences of diets
The data story can be found here: https://tormey97.github.io/food-datastory/

The notebook with the analysis work is FinalNotebook. In case you cannot see the dynamic animations correctly, you can check the notebook here:

https://nbviewer.jupyter.org/github/carlosvillasanchez/Salmon-tortilla-al-pesto/blob/master/FinalNotebook.ipynb


# Abstract
One of the most important factors in human health is how we eat. We would like to look at different diets of different countries, looking at the different types of food and drinks consumed, and see if we can draw conclusions about the healthiness of the different countries. To do this, we can compare the results with various health recommendations, such as the famous food pyramid. In doing this, we perform an analysis that can uncover deficits and problems in a nation's diet, and develop a tool that can aid in correcting these problems.

Certain health conditions are caused by malnutrition and nutritional deficits. A patient with such a condition will need to make dietary changes in order to combat the disease. However, different types of food are complex amalgamations of various nutrients, and if one wants to eat more of one specific nutrient, it could cause an increased consumption of certain other nutrients as well. Using datasets about recipes, we want to discover the correlation of the different ingredients to see if a certain nutritional recommendation may lead to an undesired indirect increase in other nutrients.


# Research questions
- What’s the difference in the consumption rate of healthy food between different age groups?
- What’s the difference in the consumption rate of healthy food for the same age group between different countries?
- What is the presence correlation between ingredients in recipes?
- Are there increases in the consumption of some ingredients when fighting against a specific disease via nutrition?
- Are there increases in the consumption of some ingredients when adhering to a specific diet, such as veganism?
- Are there some diets that are healthier than others?
- Which recipes are recommended to fight against a specific disease while not resulting in an undesirable increase of some other ingredients?


# Datasets
The datasets used are the following:
- [EFSA Comprehensive European Food Consumption Database](http://data.europa.eu/euodp/en/data/dataset/the-efsa-comprehensive-european-food-consumption-database): It has a size of 300.000 rows and 96 columns, with information related to products consumed, in which country, in which year and by which group of age among other things.
- [Recipe1M+](http://pic2recipe.csail.mit.edu): For the recipe data.


# Tema members

- Davide: Analysis of food consumption surveys, plotting for food consumption surveys, writing the introduction
- Fernando: Analysis of food consumption surveys, analysis of diet complexity, clustering of recipes
- Carlos: Analysis of the recipes dataset, analysis of diets, writing the data story 
- Torstein: Analysis of relationships between ingredients, development of the webpage and the data story
