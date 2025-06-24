🎵 Music Store Data Analysis – SQL Portfolio Project
This project explores a fictional digital music store database using SQL. The objective is to derive business insights from customer behavior, music genre preferences, and revenue trends using structured SQL queries.
________________________________________
🔬 Project Overview
The dataset simulates a music store’s operations with tables such as:
•	customer (customer details)
•	invoice & invoice_line (purchase and item details)
•	track, album, artist (music catalog)
•	employee (staff hierarchy)
•	genre (music classification)
________________________________________
💡 Key Questions Answered
✅ Easy
1.	Who is the senior most employee based on job title?
2.	Which countries have the most invoices?
3.	What are the top 3 invoice totals?
4.	Which city has the highest total invoice value?
5.	Who is the customer who has spent the most?
💠 Moderate
1.	Who are the Rock music listeners (email, name, genre)?
2.	Top 10 Rock artists by number of tracks
3.	Tracks longer than average length (with duration)
📈 Advanced
1.	How much has each customer spent on the best-selling artist?
2.	What is the most popular genre in each country?
3.	Top customer by total spend per country (supporting ties)
________________________________________
💪 Skills & Tools Used
•	SQL Joins: INNER JOIN, LEFT JOIN
•	Aggregation: SUM(), COUNT(), AVG()
•	Window Functions: RANK(), ROW_NUMBER()
•	Subqueries & CTEs
•	Filtering & Sorting
•	PostgreSQL / SQLite compatible
________________________________________
📊 Sample Output
Country	Genre	Purchases
USA	Rock	43
Germany	Jazz	30
Germany	Metal	30
________________________________________
📂 Repository Structure
Music-Store-Data-Analysis/
├── README.md                # Project overview
├── SQL/
│   └── music_store_analysis.sql
├── Excel_Output/
│   └── results.xlsx
├── Visuals/
│   └── genre_by_country_chart.png
________________________________________
