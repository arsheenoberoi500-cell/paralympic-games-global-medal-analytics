# 🏅 Paralympic Games — Global Medal Analytics

An interactive **Power BI dashboard** analyzing Paralympic Games medal performance across countries, sports, seasons, and continents from **1960 to 2018**.

This project demonstrates practical skills in **data cleaning, Power Query, DAX, data modeling, data visualization, and Business Intelligence**.

---

## 🎯 Project Objective

The objective of this project was to transform historical Paralympic Games data into an interactive Power BI dashboard.

The dashboard allows users to explore:

- Overall medal performance
- Medal trends across years
- Country-wise medal performance
- Sport-wise medal performance
- Gold, Silver and Bronze medal composition
- Medal distribution across continents
- Performance by season
- Participation across countries

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel**
- Data Cleaning & Transformation
- Data Modeling
- Data Visualization
- Business Intelligence

---

## 🧹 Data Preparation

The dataset was imported into Power BI and transformed using **Power Query**.

Key preparation steps included:

- Reviewing the dataset structure
- Cleaning and transforming the data
- Checking and correcting data types
- Preparing medal-related columns
- Structuring the data for analysis
- Filtering the dashboard to use **Overall** ranking records to avoid duplicate medal counting

---

## 📐 DAX Measures

### Total Medals

```DAX
Total Medals =
SUM('Sheet1 (2)'[npc_gold]) +
SUM('Sheet1 (2)'[npc_silver]) +
SUM('Sheet1 (2)'[npc_bronze])Calculates the combined number of Gold, Silver and Bronze medals.

Total Gold
Total Gold =
SUM('Sheet1 (2)'[npc_gold])

Calculates the total number of Gold medals.

Participating Countries
Participating Countries =
DISTINCTCOUNT('Sheet1 (2)'[npc_name])

Calculates the number of unique participating countries/NPCs.

📊 Dashboard Components

The dashboard contains 10 visuals:

🔢 KPIs
Total Medals
Total Gold Medals
Participating Countries
🎛️ Slicers
Year
Season
📈 Charts
Medal Trend by Year — Line Chart
Top 10 Countries by Total Medals — Bar Chart
Gold/Silver/Bronze Composition of Top Countries — Stacked Column Chart
Top 10 Sports by Total Medals — Stacked Bar Chart
Medal Distribution by Continent — Donut Chart
🔍 Analytical Questions

The dashboard was designed to answer questions such as:

How many medals were awarded overall?
How many Gold medals were won?
How many countries participated?
How did medal totals change over the years?
Which countries had the highest medal totals?
What was the Gold, Silver and Bronze composition of leading countries?
Which sports had the highest medal totals?
How were medals distributed across continents?
How does medal performance vary by season?
How does medal performance change when filtering by year?

🎨 Dashboard Design

The dashboard uses a modern dark theme with purple accents.

Color Palette
Element	HEX
Background	#0F0F14
Purple	#7B2CBF
Light Purple	#9D4EDD
White	#FFFFFF
Grey	#A7A7B0
Card Background	#1B1B24

💡 Skills Demonstrated
Power BI Dashboard Development
Power Query ETL
Data Cleaning
Data Transformation
Data Modeling
DAX Measures
KPI Development
Interactive Slicers
Top-N Analysis
Trend Analysis
Comparative Analysis
Data Visualization
Business Intelligence

📁 Repository Contents
Paralympic-Games-Global-Medal-Analytics/
│
├── Paralympic_Games_Global_Medal_Analytics.pbix
└── README.md

Note: The source dataset is not included in this repository.

🚀 How to Use
Download the .pbix file from this repository.
Open it using Microsoft Power BI Desktop.
Use the Year and Season slicers to explore the dashboard.
Interact with the charts to analyze medal performance.

📌 Project Highlights
Historical analysis covering 1960–2018
Interactive Power BI dashboard
3 KPI cards
2 interactive slicers
5 analytical charts
DAX-based calculations
Power Query data transformation
Top-10 country analysis
Top-10 sport analysis
Medal composition analysis
Continental medal analysis
Year and season filtering

👤 Author
Arsheen Oberoi

Data Analyst | Power BI | SQL | Python | Excel

🔗 LinkedIn:
https://www.linkedin.com/in/arsheen-oberoi-a6a5222a6

🔗 GitHub:
https://github.com/arsheenoberoi500-cell


Thank you for visiting this project.

Feel free to explore the Power BI dashboard and connect with me on LinkedIn.
