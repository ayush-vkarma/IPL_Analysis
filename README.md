📘 IPL Analysis Dashboard – Power BI Project

📊 Overview

This project presents a complete IPL (Indian Premier League) Analysis Dashboard built using Power BI.
It provides rich visual insights into:
-Batting performance
-Bowling & fielding statistics
-Toss decisions
-Venue analysis
-Overall match trends

The dashboard uses a clean IPL-themed design with interactive visuals and meaningful KPIs.

🎯 Objective

The main goal of this project is to analyze IPL match and ball-by-ball delivery data to answer:
-Who are the top-performing batsmen and bowlers?
-Which teams perform best across seasons?
-How does the toss impact match results?
-Which venues host the most matches?
-What are the key batting, bowling, and fielding trends?

🧾 Dataset Description

1. Matches Dataset
Contains match-level details:
-Match ID
-Teams
-Venue
-Season
-Toss winner & decision
-Match winner
-Player of the match

2. Deliveries Dataset
Contains ball-by-ball data:
-Batsman runs
-Bowler
-Dismissal type
-Fielder involved
-Over & ball number
-Total runs

A one-to-many relationship was created between Matches (1) and Deliveries (many) via match_id

⚙️ Methodology

1. Data Cleaning
-Standardized team names
-Removed duplicates & blanks
-Fixed dismissal inconsistencies
-Trimmed extra spaces
-Ensured relational integrity

2. Data Modeling
-Relationship between Matches and Deliveries
-Created a central Measures table
-Implemented some DAX formulas

3. Dashboard Design
-IPL-themed color palette
-Clear headers, buttons, slicers
-KPI cards, bar charts, pie charts, maps
-Page-wise story flow

📈 Dashboard Pages

🟦 1. Overview Dashboard
-Total Matches
-Total Runs & Wickets
-Matches by Season
-Team-wise Wins

🟨 2. Batting Analysis
-Top Run Scorers
-Most Sixes
-Most Fours
-Lowest Scorers

🟥 3. Bowling & Fielding Analysis
-Highest Wicket Takers
-Best Economy Rates
-Overs Bowled
-Runouts & Catches by Fielders

🟩 4. Toss & Venue Analysis
-Toss Decisions (Bat/Field)
-Toss Winners vs Match Winners
-Venue Map
-Matches by City

🔍 Key Insights

-Mumbai Indians dominate tot-al wins
-SL Malinga leads in wickets
-Chris Gayle leads in six-hitting
-Toss winners slightly prefer fielding first
-Mumbai & Bengaluru host the most matches
-MS Dhoni & KD Karthik excel in fielding dismissals

🛠 Tools Used

-Power BI Desktop
-Power Query
-DAX
-Excel/CSV datasets

🎨 Design Theme

A premium IPL color palette was used:
Purpose	Color
Primary	#0A3D91
Dark Blue	#021A3C
Gold Accent	#F7C600

The design follows:
-Consistent typography
-Visual hierarchy
-Balanced spacing
-Clean layout across pages

👨‍💻 Author
Ayush Vishwakarma — Data Analyst

LinkedIn: https://www.linkedin.com/in/ayush-d-vishwakarma
Portfolio / GitHub: https://github.com/ayush-vkarma
