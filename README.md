Customer Retention Analysis

Project Overview



This project analyzes customer retention using a store dataset. The main purpose of this project is to understand customer behavior and identify some factors related to customer retention.



Dataset



The original dataset contains 30,801 customer records and 15 columns.



The dataset includes information about customer details, order behavior, email activity, customer preferences, service usage, and customer retention.



The main target variable is retained.



After data cleaning, the dataset contained 30,747 rows.



Tools Used



Python



Pandas



NumPy



Matplotlib



Seaborn



Jupyter Notebook



Data Cleaning



The dataset was checked for missing values and duplicate records.



Missing values related to customer and order date information were removed. Date columns were also converted into datetime format.



After cleaning:



30,747 rows



15 columns



0 missing values



0 duplicate rows



Feature Engineering



The following features were created during the analysis:



service\_score



estimated\_emails\_opened



customer\_tenure



Outlier Analysis



Outliers were checked using the IQR method for:



avgorder



ordfreq



esent



The detected outliers were kept because they may represent actual customer behavior.



Customer Retention Rate



The overall customer retention rate was 79.46%.



Analysis



The project includes analysis of:



Customer retention distribution



Average order value by retention



Order frequency by retention



Email open rate by retention



Email click rate by retention



Customer retention by city



Customer retention by favorite day



Correlation heatmap



Customer retention over time



Key Findings



The overall customer retention rate was 79.46%.



Retained customers had a higher average order value.



Retained customers had a higher order frequency.



Non-retained customers had a higher email open rate.



Retained customers had a higher email click rate.



Monday had the highest number of retained customers.



BOM city had the highest number of both retained and non-retained customers.



esent (number of emails sent) had the strongest relationship with customer retention among the analyzed features.



Retention was lowest in 2008 and highest in 2013.



Conclusion



This project helped me understand customer retention using order behavior, email engagement, customer preferences, and service usage.



The analysis shows differences between retained and non-retained customers and provides useful insights into customer behavior.



Project Files



Customer Retention Analysis.ipynb - Main analysis notebook



Customer\_Retention\_Analysis\_Report.pdf - Project report



README.md - Project information

