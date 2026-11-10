# Music_Store_SQL_Project
SQL analysis of a digital music store database: customers, invoices, genres, artists, and sales trends, answered with 11 queries from basic to advanced.

#  Music Store Data Analysis using SQL

SQL analysis of a digital music store database (11 tables, ~4,700 invoice lines across 614 invoices) to answer business questions about sales, customers, artists, and genres.

## Objectives
- Find top countries, cities, and customers by revenue
- Identify the most popular genres and artists
- Pick the best city for a promotional music festival

Tables: `employee`, `customer`, `invoice`, `invoice_line`, `track`, `album`, `artist`, `genre`, `media_type`, `playlist`, `playlist_track`

##  Questions Solved
**Set 1 – Basic (8 queries):** senior-most employee, countries with most invoices, top 3 invoice totals, best festival city, best customer, rock music listeners, top 10 rock artists, tracks longer than average.

**Set 2 – Advanced (3 queries):** customer spend per artist, top genre per country, top customer per country.

##  Key Insights
- **Senior-most employee:** Mohan Madan (Senior General Manager, level L7)
- **Most invoices:** USA (131), followed by Canada (76) and Brazil (61)
- **Best festival city:** Prague, with $273.24 in total invoices
- **Best customer:** František Wichterlová, with $144.54 spent
- **Top rock artist:** Led Zeppelin (114 tracks), then U2 (112) and Deep Purple (92)
- **Most popular genre overall:** Rock (2,635 units sold), far ahead of Metal (619)

## Tech Used
PostgreSQL · Joins · Subqueries · CTEs · Window Functions · Aggregations

##  Repository Structure
```
├── Music_Store_database.sql            # Database dump
├── Music Store- Create Tables Query.txt
├── Music_Store_Analysis_Query.sql      # All 11 analysis queries
├── Music_Store_Analysis-Questions.pdf  # Problem statements
├── Music_Database_Schema.jpg           # ER diagram
└── *.csv                               # Source data for each table
```


