# Analyzing-the-Impact-of-Car-Features-on-Price-and-Profitability
This dataset contains details on approximately 11,000 car models, including make, model, year, engine specifications, gearbox type, fuel efficiency, market category, size, and manufacturer's suggested retail price (MSRP).

# Project Description:
## Overview:
The automotive industry is undergoing tremendous transformations as a result of a
focus on fuel efficiency, environmental sustainability, and technological innovation.
Understanding consumer demand for cars is critical for car manufacturers to stay
competitive in this dynamic landscape. This initiative attempts to help a car
manufacturer maximize profitability by improving pricing and product development
decisions. The goal is to give relevant insights that align with consumer preferences and
create corporate success by leveraging the power of data analysis.

Data Cleaning and Preprocessing Steps:
Before beginning the data analysis journey, we prioritize extensive data cleaning and
preprocessing activities to ensure accurate and dependable outcomes. This critical
phase includes addressing missing data, deleting duplicates, converting data types,
finding and treating outliers, scaling numerical variables, and transforming the data as
needed. Furthermore, we standardize market categories to reduce complexity and
improve analysis results. By properly preparing the data, we lay the groundwork for
effective exploratory data analysis and model creation, allowing the automobile
manufacturer to make educated decisions.
Interactive Dashboard Building:
The data analysis culminates in the creation of an interactive dashboard using advanced
Excel skills. The dashboard addresses the client's specific questions and visualizes the
distribution of car prices by brand and body style, the average MSRPs across different

car brands and body styles, and the impact of different features on MSRP, among other
insights. I employed filters and slicers to ensure user-friendly interactivity, enabling the
car manufacturer to make strategic decisions in real-time.
Conclusion:
This data-driven approach provides the car manufacturer with a competitive edge in
understanding consumer preferences, optimizing pricing strategies, and guiding
product development efforts. By leveraging the power of data analysis and an interactive
dashboard, we empower the manufacturer to navigate the rapidly changing automotive
landscape successfully. The project's comprehensive insights and actionable
recommendations drive long-term profitability and cater to the evolving demands of the
automotive market.
# Approach
## Data Cleaning Process:
## 1. Imputations:
● Engine Cylinder (Blanks) for Electric: In the "Engine Cylinder" column, I
observed blank entries for electric cars since they do not have cylinders. To
maintain consistency and accuracy, I replaced these blank entries with "0" to
indicate that electric cars have zero cylinders. A total of 10 blank entries were
imputed.
● Engine Fuel Type Imputation: Some rows in the dataset had missing values in
the "Engine Fuel Type" column. However, the corresponding MPG city and
highway averages matched those of "flex-fuel (unleaded/natural gas)" vehicles.
Therefore, I imputed the missing values with "flex-fuel (unleaded/natural gas)"
for these rows to ensure data consistency. A total of 3 missing values were
imputed.

## 2. Deletion:
● Removal of Rows with Blank Engine HP: I removed 69 rows from the dataset
that had blank entries in the "Engine HP" column. Engine horsepower is a crucial
attribute for analysis, and to ensure accurate results, I decided to remove these
rows.
● Removal of Rows with Blank Engine Cylinder: Additionally, I removed 20 rows
from the dataset that had blank entries in the "Engine Cylinder" column. As the
number of cylinders impacts various car performance aspects, removing these
rows is essential for accurate analysis.
After performing data cleaning, the dataset was refined, resulting in 11,826 rows and 16
columns. Initially, the dataset had 11,915 rows.
Data analysis tool pack was also used to find out regression values and to identify the most
important variables in determining the MSRP of a car.

Apart from this, my approach was also to include dashboards wherever necessary to
make the analysis interactive and easily understandable to the user.
