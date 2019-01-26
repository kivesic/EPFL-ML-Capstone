# EPFL-ML-Capstone

## Course Capstone Project - Analysis of Cross-Border Commuters in Switzerland
This repository contains the capstone project done in the scope of the EPFL Extension School "Applied Data Science: Machine Learning" programme (https://exts.epfl.ch/courses-programs/applied-data-science-machine-learning). 

The analysis is based on the data provided by the Federal Statistical Office of Switzerland and can be accessed https://www.bfs.admin.ch/bfs/en/home/services/recherche/stat-tab-online-data-search.html. 

The data contains the per quarter count of cross-border commuters in Switzerland (also expressed per canton, gender, and age group). It was fetched in November, 2018 and it contains the statistics until the 3rd quarter of 2018. 

The repository contains the following files:
* Project.ipynb - Jupyter notebook with analysis
* cross_border.csv the data file (the format of the data was slightly changed to make it readable by Jupyter).

After reading the data and providing basic insigghts in the data, the data integrity is checked, and the plots show the the trends in commuters number per gender, age-group, and canton. Finally, the predictions are provided and evaluated for the future number of cross-border commuters relying on historical data.
