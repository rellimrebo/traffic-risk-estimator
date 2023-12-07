# Traffic-Risk-Estimator
Visualization of San Diego traffic risk based on historical collision data

Team members: Andrew Obermiller, Haoran Li, Joey Liu, Tongqing Shi, Zachary Zheng
# Files

veh_type_graphs.ipynb: Visualization of vehicle types involved in collisions and normalized casualty rates.

visualization.ipynb: Visualization of time and street information in collisions.

data_statistical.ipynb: Apply some Probability and Statistical Methods on the processed traffic and collisions data.

Classification.py: A classification model using Logistic Regression to predict whether there will be a collision.  

Regression.py: A regression model using Linear Regression to predict the number of people who will be injured by the collision. 

# How to run these scripts
## For data analysis:

data_preprocessing.py:
1. Download pd_collisions_details_datasd.csv and traffic_counts_datasd.csv
2. Ensure the script and datasets are the in the same directory
3. Ensure all third party modules are installed
4. Run 

veh_type_graphs.ipynb:
1. Download pd_collisions_details_datasd.csv
2. Ensure the script and dataset are the in the same directory
3. Ensure all third party modules are installed
4. Run

## For prediction:
1. Download the collision_report_processed.csv
2. Download the Classification.py and Regression.py
3. Put them into the same dictionary.
4. Run these two python files and you will get the output.

# Third Party Modules
csv  
Ridge  
numpy  
LogisticRegression  
random  
matplotlib.pyplot  
