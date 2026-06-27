OIBSIP Task 2: Exploratory Data Analysis (EDA) on Google Play Store Dataset
Project Overview
This project performs Exploratory Data Analysis (EDA) on the Google Play Store dataset to identify trends and patterns related to app categories, ratings, pricing, and installs. The dataset contains information on over 10,000 Android applications collected from Kaggle. Using Python, the data was cleaned, analyzed, and visualized to generate meaningful business insights.
Dataset
Source: Kaggle – Google Play Store Dataset
Records: 10,000+ Android apps
Steps Performed
Data Cleaning
Removed 483 duplicate app records.
Filled missing values in the Rating column using the mean rating.
Converted Installs, Price, and Size columns into numeric format.
Removed one invalid row where Category = '1.9'.
Final cleaned dataset size: 9,366 rows × 13 columns.
Data Visualization
Top 10 App Categories (Bar Chart)
Free vs Paid Apps Distribution (Pie Chart)
App Rating Distribution (Histogram)
Reviews vs Installs (Scatter Plot)
Price Distribution of Paid Apps (Box Plot)
Key Insights
FAMILY and GAME are the most popular app categories.
Around 92.6% of apps are free, while only 7.4% are paid.
The average app rating is 4.17, with most ratings between 4.0 and 4.5.
Apps with more reviews generally have higher install counts.
Most paid apps cost less than $5, with a few expensive outliers.
Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
How to Run
Install the required libraries:
Bash
pip install pandas numpy matplotlib seaborn
Open googleplaystore_Analysis_Saquib.ipynb in Jupyter Notebook.
Run all cells to reproduce the analysis and visualizations.
Author
Aasari Wajid  
Data Analyst Aspirant | Python | SQL | Advanced Excel | Power BI
