# sushmita395
🏏 EWU Cricket Tournament Database Project
📌 Overview
The EWU Cricket Tournament Database Project is a relational database system developed to manage and analyze cricket tournament data.
It captures detailed match-level and ball-by-ball information and provides advanced analytical queries to extract meaningful cricket statistics.

This project was created as part of an academic Database Systems course at East West University (EWU).

🗂️ Database Features
Complete match and season management
Ball-by-ball data tracking
Batting and bowling statistics
Team performance analysis
Venue-based performance insights
Toss and match result analysis
Advanced SQL reporting using CTEs and window functions
🏗️ Database Schema
The database consists of the following major entities:

Match
MatchResult
Team
Player
Season
Venue
Ball_By_Ball
ScoredRuns
ExtraRuns
WicketTaken
Toss
Umpire
Umpired_By
Season_Team_Player
All tables are properly normalized and connected using Primary Keys and Foreign Keys to maintain data integrity.

📁 Project Files
File Name	Description
Create.sql	Contains all CREATE TABLE statements and primary key definitions
Further.sql	Defines all foreign key constraints and relationships
Query_Report.sql	Contains advanced SQL queries and analytical reports
📊 Key SQL Reports
The project includes queries for:

Batting statistics (runs, strike rate, 50s, 100s)
Bowling statistics (wickets, economy, averages)
Team performance by season
Successful run chases above 180
Venue-wise batting averages
Highest innings totals
Most wickets per season
Most sixes per season
Toss impact analysis
Head-to-head team analysis
Top ducks, catches, extras, and worst economy rates
🧠 SQL Concepts Used
Common Table Expressions (CTE)
Window Functions (RANK(), ROW_NUMBER())
Aggregate Functions
Complex Joins
Subqueries
Data Filtering & Grouping
Referential Integrity Constraints
🛠️ Technology Stack
Database: Oracle SQL
Language: SQL
Tools: SQL Developer / Any Oracle-compatible DB tool
🎓 Academic Context
University: East West University (EWU)
Project Type: Database Management System Project
Domain: Sports Analytics (Cricket)
✅ How to Run
Execute Create.sql to create all tables.
Execute Further.sql to apply foreign key constraints.
Insert required data into tables.
Run Query_Report.sql to generate analytical reports.
📜 License
This project is for educational purposes only.

🙌 Acknowledgement
Special thanks to course instructors and teammates for guidance and collaboration throughout this project.
