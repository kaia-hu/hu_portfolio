# Double the Joy: Leveraging 2-Stage Stochastic Optimization to Plan the Ultimate NYC Tour
## Group Members: Kaia Hu, Hannah Nguyen, Megan Ty, and Jhanvi Udani <br>
### Executive Summary
To assist tour group operators and travel agencies in designing tours that appeal to the
mass market, we developed an optimization algorithm to identify the ideal combination of
attractions in a region that maximizes happiness for potential tourists. <br>
Using New York City as a sample, we collected data on top attractions, including their
attendance costs, and categorized each attraction based on its alignment with seven key tourist
attributes: nature, museum, family-friendly, activity, walking, theater, and landmark. To better
understand tourist preferences, we conducted a survey and applied K-Means clustering to group
the potential market into four distinct tourist archetypes, each with its respective frequency and
average preferences across the seven attributes. <br>
In this algorithm, happiness is defined as the alignment between an attraction’s attributes
and the preferences of the tourist group. As such, the objective function is a weighted sum of the
selected attractions, where the weights are determined by how well each attraction matches the
preferences of the group. Since the composition of the tour group is uncertain, we calculate
happiness across the four possible tourist archetypes and use expected happiness as the basis for
optimization. <br>
The algorithm was implemented in Python. We ran initial tests on the model and
evaluated its performance under varying budget constraints and changes in the probabilities of
tourist archetypes. Preliminary findings suggest that the model is more sensitive to changes in
potential happiness weights rather than the probability of a given tourist archetype or the total
budget. As such, future work should focus primarily on collecting a comprehensive dataset for the
attractions and how well they can align with the market’s preferences. <br>
This initial implementation has the potential for a robust tool that can identify optimal
itineraries within cities or across continents. As the algorithm evolves to handle larger datasets
and more constraints - particularly travel time, unhappy guests, and their associated costs - a
Backwards Induction model will likely be more suitable to address the added complexities <br>
### Data Dictionary
- nyc_attractions.csv: The list of New York City tourist attractions with their correpsonding relevance to a certain tourist preference category
- survey_final_table.csv: The survey final observation of four tourist archetypes and their preferences over different attraction categories. <br>
Both files should be run in the notebook as they are the main data used in this study. 
