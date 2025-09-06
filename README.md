**Aim of the Project**

The aim of this project is to analyze luxury housing sales data to gain meaningful insights for builders, investors, and buyers. The process involves:

1) Data Extraction

Collect raw dataset (Luxury Housing Bangalore).

Load it into Python (Pandas) for analysis.

2) Data Transformation & Preprocessing

Handle missing values in key columns (Unit Size, Ticket Price, Amenity Score).

Standardize categorical values (e.g., Micro Market names, Configurations like 3BHK/4BHK/5BHK).

Create derived fields such as Price per Sqft and Amenity Category.

Save the cleaned dataset as Luxury_Housing_Cleaned.csv.

3) Database Insertion (PostgreSQL)

Create a PostgreSQL schema for housing sales data.

Insert cleaned dataset into the database using Python (SQLAlchemy).

Run validation SQL queries (e.g., Avg Ticket Price per Micro Market, Demand by Configuration).

4) Data Analysis & Visualization (EDA)

Use Python (Pandas, Matplotlib, Seaborn) to explore patterns.

Key analysis:

Avg Ticket Price per Micro Market

Configuration Demand (2BHK, 3BHK, 4BHK, 5BHK)

Amenity Score vs Ticket Price

Connectivity vs Price per Sqft

Buyer Type Distribution

5) Dashboard Creation (Tableau / Power BI)

Connect PostgreSQL database to Tableau.

Build interactive dashboard with visuals:

Sales by Micro Market

Price Trends over Time

Buyer Type & NRI Distribution

Amenity & Connectivity Impact on Pricing

Configuration Demand Comparison
