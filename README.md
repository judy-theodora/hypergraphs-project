This directory contains all the Python notebook files used to generate the graphs/hypergraphs, as well as generate the data plots used in the final project writeup.
Below is a list of the notebook files with a description of each.
All the data needed for each file is stored in the 'data' and 'pickle' folders, so these files can be used in any order.

This project was published in *New Ideas in Psychology*, with the help of Massimo Stella, Salvatore Citraro, Federico Battiston, Cynthia Siew, and Giulio Rossetti.  
https://doi.org/10.1016/j.newideapsych.2023.101034


aoa_prediction.ipynb
--------------------
*Use this file to generate the plots of data for AoA prediction.*
This is where the age of acquisition predictions are made, with a random forest regressor. Correlation metrics are also calculated here.

ranking_prediction.ipynb
------------------------
*Use this file to generate the plots of data for the ranking prediction.*
This is where the XGBoost ranker is trained for the ranking task. Correlation metrics are calculated too.

graph_construction_aoa.ipynb
----------------------------
In this notebook we construct the pairwise graph model and tables of data for use in the AoA prediction. 

hypergraph_construction_aoa.ipynb
---------------------------------
This notebook constructs the hypergraph model and constructs the tables of data for use in the AoA prediction. 

graph_construction_ranking.ipynb
--------------------------------
This notebook constructs the graph and hypergraph models and constructs the tables of data for use in the ranking prediction.


