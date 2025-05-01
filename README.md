📝 Netflix Data Analytics Project – Description
This project is an end-to-end data analytics case study where I analyzed Netflix’s global titles dataset using a complete data pipeline involving Excel, MySQL, and Power BI. The goal was to extract insights about content trends, regional production patterns, and platform growth using professional data cleaning and dashboarding techniques.

⚒️ Tools & Technologies Used
Step	Tool	Purpose
1️⃣	Excel	Data cleaning: Split columns (using Text to Columns with ,), removed nulls, used TRIM, IFERROR, etc.
2️⃣	MySQL	Structured queries: Cleaned data again using SQL (e.g., TRIM(), IS NULL, CASE, DATE functions, etc.), filtering, joins, and exporting ready data
3️⃣	Power BI	Connected to MySQL server, imported cleaned data, changed data types, built relationships (data modeling), and created interactive dashboards with filters, cards, slicers, and graphs

🧹 Key Steps Performed
Data Cleaning in Excel

Used Text-to-Columns (split on commas ,)

Applied TRIM(), IFERROR(), and manual filtering

Removed blank rows, null values, and corrected headers

Import to MySQL

Uploaded the cleaned CSV to a MySQL table

Wrote SQL queries using:

SELECT, WHERE, ORDER BY, LIMIT

TRIM(), LOWER(), UPPER()

IS NULL, NOT NULL

Used DATE functions to extract Year, Month

Created new tables/views with filtered data

Connect to Power BI

Connected MySQL as data source

Performed Data Modeling:

Changed data types: Dates, Text, Boolean, etc.

Set primary keys and relationships (1-Many, etc.)

Built Interactive Dashboard:

Used Slicers, Cards, Bar/Column Charts, Pie Charts, Date filters

Created 2 report pages with different visuals and filters

📊 Insights Uncovered
Count of Movies vs TV Shows

Content addition trend over years

Country-wise production volume

Top genres and categories

Rating breakdowns and maturity insights

Popular release years and runtime patterns

📁 Project Files
netflix_titles (raw).csv → Original raw dataset

netflix_titles.csv → Cleaned dataset after Excel

.sql script (optional) → Queries used in MySQL

Netflix Dashboard.pbix → Power BI report

Screenshot1.png, Screenshot2.png → Report page previews

README.md → Project overview

📌 What I Learned
Real-life data is always messy: how to clean and format properly

Practical use of SQL in preparing datasets for BI tools

Importance of data modeling before visuals

How to create a complete Power BI dashboard with KPIs, visuals, and filters

End-to-end data analytics workflow for freelancing and portfolio
