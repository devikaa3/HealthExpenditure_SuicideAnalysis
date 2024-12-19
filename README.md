# HealthExpenditure_SuicideAnalysis
This project analyzes the relationship between health expenditure and suicide rates using a dataset obtained from Kaggle. The analysis highlights the connection between higher healthcare expenditure and lower suicide rates, suggesting the importance of investing in healthcare services for mental health and overall well-being. The dataset includes various health and demographic indicators, such as population, health expenditure, mental health expenditure, and suicide rates across different countries and years
The dataset is sourced from the World Health Organization (WHO) Mortality Statistics and uses the International Classification of Diseases, 10th Revision (ICD-10) codes to classify causes of death. It contains the following columns
Country: Name of the country
Year: Year of the data entry
Population: Population of the country
Deaths_All_Types: Total number of deaths
Deaths_Suicides: Number of suicides according to ICD-10
HExp_Pctage_Y: Health expenditure as a percentage of GDP
MHExp_Pctage_20: Mental health expenditure index (2011)
Dep_Num_2015: Depression estimate index (2015)
Suicide_p100: Number of suicides per 100,000 population
Python: A powerful programming language used for data manipulation and analysis.
Pandas: Python library for data manipulation and analysis.
NumPy: Python library used for numerical computing and array manipulation.
Tableau: Data visualization software used to create visual representations of the data, such as geo maps, line charts, bar charts, area charts, and tree maps.
Google Colab: A cloud-based platform for writing and running Python code in a Jupyter notebook environment.
Data Preprocessing Steps:
Library Imports: Required Python libraries are imported, including Pandas and NumPy, for data manipulation.
Data Loading: The dataset is loaded into a Pandas DataFrame from a CSV file.
Descriptive Analysis: Preliminary analysis is done to understand the dataset's main features.
Null Value Check: Null or missing values are checked and handled.
Outlier Detection: Outliers in the data are detected and analyzed.
Data Visualization: The cleaned data is visualized using Tableau. Graphs such as geo maps, tree maps, line charts, bar charts, and area charts are used to explore relationships between health expenditure and suicide rates.
Visualizations:
Geo Maps: Visualize data on maps, showing country-specific health expenditure and suicide rates.
Line Chart: Show trends over time for suicide rates and depression estimates.
Bar Chart: Display country-specific health expenditure and suicide rates.
Tree Map: Visualize hierarchical data related to health indicators and suicide rates.
Area Chart: Represent the relationship between different health indicators and suicide rates.
Key Insights
•	Brazil has the highest population.
•	Latvia had the highest suicide rate in 2000, while Cyprus had the lowest in 2004.
•	Moldova had the highest health expenditure in 2009.
•	Thailand has a suicide rate of 56.0 and health expenditure of 61.5.
Conclusion:
The analysis shows a negative correlation between health expenditure and suicide rates, suggesting that countries investing more in healthcare, especially mental health services, tend to have lower suicide rates. Further analysis is required to better understand the complex relationship between health expenditure, mental health, and suicide rates.
