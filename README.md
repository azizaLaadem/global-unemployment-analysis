Global Unemployment Analysis
This project analyzes the evolution of global unemployment by region, income level, and key economic indicators. It combines data science, machine learning, and business 
intelligence to deliver a comprehensive view of global labor trends.

Project Objectives : 

Analyze global unemployment trends since the year 2000
Compare unemployment across world regions and income groups
Identify economic factors correlated with unemployment
Build a Random Forest model to capture non-linear relationships
Integrate machine learning outputs directly into Pow

Data Sources :
All data is extracted from the World Bank Open Data platform:
Unemployment rate (SL.UEM.TOTL.ZS)
GDP per capita (NY.GDP.PCAP.CD)
Total population (SP.POP.TOTL)
School enrollment rate (SE.SEC.ENRR)

Data Preparation :
Data preprocessing was performed in Python and includes:
Handling missing values
Normalizing numerical variables
Merging multiple World Bank datasets
Creating a cleaned dataset (dataset_nettoye.csv)
Encoding categorical fields

Machine Learning Model: Random Forest :
A Random Forest model was built to:
Capture non-linear relationships
Assess feature importance

Top 3 Most Important Features: 
1. Total population
2. School enrollment rate
3. GDP per capita

The model was run in:
Jupyter Notebook (development stage)
Power BI using the Python Script Visual (for integration and result comparison)

Power BI Dashboard
The dashboard contains four pages:

Technical Pages (2 pages) :
Data preprocessing summary
Correlation analysis
Random Forest feature importance
Comparison of Jupyter vs Power BI model outputs

Executive Pages (2 pages) :
Unemployment trends by region
Analysis by income level
World map visualizations
Predictive insights
Key takeaways for policy makers and executives

Technologies Used
Python: Pandas, Scikit-learn, Matplotlib
Power BI: DAX, Python Script Visual, interactive dashboards
Git & GitHub: Version control and documentation

How to Run the Project : 

1. Clone the repository:
git clone https://github.com/azizaLaadem/global-unemployment-analysis.git
2. Open the notebook:
Run model/unemployment_analysis.ipynb
3. Open the Power BI dashboard:
Load dashboard/analyse.pbix

Contact :
For feedback, suggestions, or collaboration:
👉 LinkedIn: Aziza Laadem

   
