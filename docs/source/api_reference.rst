API Reference
=============

This section summarizes the conceptual backend functions used inside the project.

Database Access
---------------
**fetch_ingredient(name)**  
Retrieves ingredient nutrient data from MySQL.

**search(keyword)**  
Returns a list of ingredient names matching the keyword.

Nutrition Calculation
---------------------
**calculate_nutrients(ingredients, quantities)**  
Aggregates calories and nutrients using Pandas.

Optimization Engine
-------------------
**optimize_portions(targets, ingredients)**  
Computes ideal ingredient amounts based on user goals.

Nutrient Density Tools
----------------------
**rank_by_density(nutrient, count)**  
Returns top-k foods for the selected nutrient.

**filter_by_range(nutrient, low, high)**  
Filters foods within nutrient-per-calorie range.
