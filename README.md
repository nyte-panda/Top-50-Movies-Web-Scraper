# 🎬 Top 50 Films Scraper

This project scrapes the **Top 50 Highly-Ranked Films** from an archived EverybodyWiki page, saves the data into a **CSV file** and a **SQLite database**.

---

## 📋 Project Description

The script:
- Scrapes **Average Rank**, **Film Title**, and **Release Year** for the top 50 films.
- Saves the scraped data into:
  - A CSV file: `top_50_films.csv`
  - A SQLite database: `Movies.db` (table: `Top_50`)

---

## 🛠️ Built With

- Python 3
- requests
- BeautifulSoup (bs4)
- pandas
- sqlite3

---

## 📂 Files Included

| File Name         | Description                        |
|-------------------|------------------------------------|
| `scraper.py`       | Python script for scraping and saving data |
| `top_50_films.csv` | CSV file containing the film data |
| `Movies.db`        | SQLite database with a `Top_50` table |

---

## 🚀 How to Run

1. Clone the Repository
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
