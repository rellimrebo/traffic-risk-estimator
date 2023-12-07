# Traffic-Risk-Estimator
Visualization of San Diego traffic risk based on historical collision data

Team members: Andrew Obermiller, Haoran Li, Joey Liu, Tongqing Shi, Zachary Zheng
# Files
veh_type_graphs.ipynb: Visualization of vehicle types involved in collisions and normalized casualty rates.

visualization.ipynb: Visualization of time and street information in collisions.

data_statistical.ipynb: Apply some Probability and Statistical Methods on the processed traffic and collisions data.

Classification.py: A classification model using Logistic Regression to predict whether there will be a collision.  

Regression.py: A regression model using Linear Regression to predict the number of people who will be injured by the collision.  

traffic_counts_datasd.csv: original dataset including traffic count data.  

traffic_count_dictionary_datasd.csv: the dictionary for the traffic_counts file.  

pd_collisions_details_datasd.csv: original dataset including the collisions.  

pd_collisions_details_dictionary_datasd.csv: the dictionary for the collisions_details file.  

cleaned_acc_data.csv: cleaned traffic_account_datasd.csv file that will be used in data analysis.  

cleaned_traffic_data.csv: cleaned pd_collisions_details_datasd.csv file that will be used in data analysis.  

collision_reports_processed.csv: cleaned traffic_account_datasd.csv file that will be used in predictions.  

# How to run these scripts
## For data analysis:

data_preprocessing.py:
1. Download pd_collisions_details_datasd.csv and traffic_counts_datasd.csv
2. Ensure the script and datasets are the in the same directory
3. Ensure all third party modules are installed
4. Run

data_statistical.ipynb:
1. Download collision_reports_processed.csv and traffic_counts_processed.csv
2. Ensure the script and datasets are the in the same directory or change the file path in the read_csv function
3. Ensure all third party modules are installed
4. More detailed description step by step can be found in the ipynb file, hope you can find something interesting results in this file.
5. Run


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
