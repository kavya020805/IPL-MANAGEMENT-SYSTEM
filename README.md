# 🏏 IPL Tournament Database Management System

A comprehensive database management system built to handle the operations and data of the **Indian Premier League (IPL)**, including team and player information, auction processes, match scheduling, performance tracking, and reports for different stakeholders.

---

## 📌 Objective

Design and implement a **PostgreSQL**-based relational database to manage IPL tournaments. This includes capturing data related to players, teams, matches, stadiums, sponsors, coaches, and officials, while ensuring efficient querying and reporting through normalization (up to BCNF).

---

## 👥 Team Members

- Prince Chovatiya (202301067)  
- Krish Makwana (202301103)  
- Kavya Chauhan (202301116)  
- Abhishek Kothari (202301128)  
- Yogesh Bagotia (202301114)  

---

## ⚙️ Features

### 👥 Users
- **Viewers/Fans**: Access player stats, team details, match results, standings, and MVP rankings.
- **Team Owners/Managers**: Manage team squads, auction processes, financial reports, and performance summaries.
- **Players**: Register, update details, participate in auctions, and track performance stats.
- **Match Officials**: Register and record match decisions and officiating stats.
- **Tournament Admins**: Schedule matches, update live scores, manage points table, and generate comprehensive reports.

---

## 🗃️ Project Components

### ✅ Data Design
- **ER Diagram** – Captures all entities and relationships (Player, Team, Coach, Match, Stadium, etc.).
- **Relational Schema** – Derived from ERD and validated against real-world scenarios.
- **Functional Dependencies** – Identified and minimized to derive candidate keys.
- **Normalization** – All relations normalized up to **BCNF**.

### 🧩 Schema Implementation
- `DDL.sql` – Defines all tables, data types, primary & foreign keys.
- `DML.sql` – Sample data entries using PostgreSQL.
- `Queries.sql` – Complex SQL queries to fetch insights like top scorers, team stats, auction outcomes, etc.

---

## 📊 Key Data Tracked

- Player Stats: Runs, wickets, strike rate, boundaries, etc.
- Match Info: Type, venue, umpires, man of the match, etc.
- Season Details: Title sponsors, winning & runner-up teams, MVPs.
- Team Info: Coaches, owners, auctioned players, and finances.
- Stadium Attributes: Name, city, pitch conditions, capacity.

---

## 🔍 Sample Queries

- List players of a specific team for a given season
- Get match results by date range or stadium
- Fetch auction outcomes and player prices
- Compute net run rate and points table
- Retrieve top MVPs over multiple seasons

---

## 🚀 Future Enhancements

- 🔐 Role-based access control with external views
- 🌐 Integration with a web interface for dynamic query execution
- 📈 Visual analytics dashboards for admins and fans

---

## 🧾 Reports

The system includes custom report generation for:

- Team managers (earnings, win/loss stats, player performance)
- Players (career stats, improvement areas)
- Match officials (accuracy reports)
- IPL admins (tournament-wide analysis)

---

## 🏁 Conclusion

This project offers a scalable, normalized, and query-optimized system to manage the complete lifecycle of the Indian Premier League — empowering fans, teams, players, and officials through efficient data access and analysis.

---

