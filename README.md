# Urban-Computing-Final-Project


Datasets 

https://catalog.data.gov/dataset/violence-reduction-victim-demographics-aggregated 

https://catalog.data.gov/dataset/crimes-one-year-prior-to-present 
https://data.cityofchicago.org/Transportation/CTA-L-Rail-Lines/xbyr-jnvx/about_data
https://data.cityofchicago.org/Transportation/CTA-System-Information-List-of-L-Stops/8pix-ypme/about_data

Shapefiles

https://data.cityofchicago.org/Transportation/CTA-L-Rail-Lines/xbyr-jnvx/about_data
https://data.cityofchicago.org/dataset/CTA-L-Rail-Stations-Shapefile/vmyy-m9qj/about_data
https://data.cityofchicago.org/Public-Safety/Police-Stations-Shapefiles/tc9m-x6u6/about_data




Notebooks

Exploratory-Data-Analysis.ipynb
This notebook performs Exploratory Data Analysis (EDA) on two datasets:
Dataset 1: Violence Reduction Victim Demographics Aggregated
Dataset 2: Crimes for One Year Prior to Present.
EDA steps, like loading the dataset, inspecting its structure, and preparing it for further analysis.
The notebook uses libraries like Pandas, Matplotlib, and Seaborn to clean, analyze, and visualize data.
Violence Reduction Victim Demographics Aggregated saved in db_one_cleaned.csv
Crimes for One Year Prior To Present saved in db_two_cleaned.csv

Seasonal-Analysis.ipynb
This notebook conducts Seasonal Crime Analysis for the years 2023-2024. Here’s a summary of the key tasks performed:
Temporal features such as Month and Season (Winter, Spring, Summer, Fall) are derived from the occurrence date.
Seasonal Trends Analysis:
Crime counts are grouped and analyzed by Season and Primary Crime Description.
A stacked bar chart is plotted to visualize seasonal trends for different crime types.
The analysis provides insights into how crime occurrences vary by season and location, focusing on visual representation using Matplotlib.

Machine-Learning-Models.csv
This notebook focuses on Machine Learning Model Development.
Models such as Random Forest, Logistic Regression, Gaussian Naive Bayes, and Decision Trees are likely applied.
Metrics like accuracy, precision, recall, F1-score, and ROC-AUC are used to evaluate model performance.
Handling Imbalance:
Preprocessing: Encoding, scaling, and balancing data using SMOTE.
Cross-Validation: Using Stratified K-Fold for fair model evaluation.
Model Evaluation: Accuracy, Precision, Recall, F1-score, and ROC-AUC metrics are computed.

Crime-Analysis-By-Time-Of-Day.ipynb
The notebook analyzes crime data by classifying occurrences into time-of-day categories (Morning, Afternoon, Night). 
It involves loading a dataset, cleaning time fields, categorizing data, and visualizing crime distributions using Matplotlib. 
The focus is on understanding crime patterns based on specific time windows.

Violence-Reduction-Aggregated-Analysis.ipynb 
This notebook analyzes crime trends and distributions:
Key Activities:
1. Crime Type Distribution: Visualizes the frequency of various crime types using bar plots.
2. Temporal Analysis: Converts date-time fields for analysis and categorizes data by year and quarter.
3. Yearly Crime Trends: Plots yearly trends in crime counts to observe overall patterns.
The notebook combines Pandas for data manipulation and Matplotlib/Seaborn for visualizations.

D2 Final.ipynb 

The notebook analyzes crime trends using a combination of temporal, spatial, and categorical analysis techniques. Here’s an overview of the tasks performed.

Key Sections:

Temporal Analysis: Understanding Crime Trends Over Time
This section likely analyzes trends and patterns of crimes over specific time frames.

Spatial Analysis: Visualizing Crime Locations
Crime locations are visualized on maps using spatial analysis techniques.

Categorical Analysis: Top Crime Types
Identifies and visualizes the most common types of crimes. Factors Influencing Crime Type and Arrest Likelihood
Examines various factors influencing different crime types and the probability of arrests.

Spatial Analysis: Identifying Spatial Crime Clusters Using DBSCAN
Utilizes the DBSCAN clustering algorithm to identify spatial crime hotspots.
Mapping Police Stations
Visualizes police station locations on the map.
Identifying Critical Stations in the Network Using Graph Theory.

Applies graph theory to determine the network's critical nodes(transit stations).
Libraries imported:
Pandas, NumPy, Matplotlib, and Seaborn for data manipulation and visualization.
Folium for interactive maps.
GeoPandas, Shapely, and Contextily for spatial data.
Scikit-learn's DBSCAN for clustering analysis.
NetworkX for graph theory-based analysis.

Summary of Tools and Techniques:
Visualization: Heatmaps, charts, and spatial maps using Folium and Matplotlib.
Clustering: DBSCAN to identify crime clusters.
Graph Theory: NetworkX for critical station identification.
Spatial Analysis: Geospatial libraries like GeoPandas and Contextily.


Install the following libraries to run the code in D2final.ipynb 

pip install pandas numpy matplotlib seaborn folium geopandas contextily scikit-learn shapely networkx

Datasets used - 
db_two_cleaned.csv
CTA_-__L___Rail__Lines_20241216.csv
CTA_-_System_Information_-_List_of__L__Stops_20241216.csv

Shapefiles used - 
CTA_RailStations.shp
PoliceStationsDec2012.shp
CTA - 'L' (Rail) Lines_20241216\geo_export_778fba51-19ef-45f6-b9ec-51528278b7a6.shp
