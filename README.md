-📖 Project Overview
This project focuses on the end-to-end process of Data Acquisition, Cleaning, and Exploratory Data Analysis (EDA). 
The goal was to transform raw transactional data into a structured format suitable for high-level business intelligence in Tableau.
-🗂️ Data Acquisition & SourceDataset: Global Retail Sales (Publicly sourced).
Attributes: Includes Product Descriptions, Revenue, Country, and Quantity.
Format: Structured CSV/Excel.
-🧹 Data Preparation (The "Cleaning" Phase)Before building the dashboard, 
I performed the following steps to ensure data integrity:
Handling Nulls: Removed transactions missing Description labels to prevent "Unknown" categories in visuals.
Data Type Casting: Converted Revenue to a decimal format and assigned Country a Geographic Role in Tableau.
Filtering: Applied a filter to exclude zero or negative revenue values (returns) to focus on top-line growth.
-📈 Exploratory Data Analysis (EDA) FindingsBased on the initial analysis in Tableau:
Top Performer: The "Regency Cakestand" is the highest revenue-generating product, crossing the $160,000$ mark.
Market Dominance: The United Kingdom represents the largest market share by a significant margin.
Product Synergy: Items like "Party Bunting" and "Jumbo Bag Red" show high sales volume across multiple European territories (Switzerland, France, Spain).
-🖼️ Dashboard StoryboardThe dashboard is designed to follow a logical "Data Story" flow:
The "Where": A Global Map highlighting revenue by country (Top 10 Country Revenue).
The "What": A Ranking of products to identify the core inventory drivers (Best Selling Product).
The "Details": A granular breakdown of how specific products perform within individual countries.
-🛠️ Tools UsedTableau Public: 
For visualization and dashboarding.
Excel/SQL: For initial data cleaning and inspection.
