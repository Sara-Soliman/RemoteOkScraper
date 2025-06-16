# RemoteOK Web Scraper

Scrapes remote job listings from [RemoteOK.com](https://remoteok.com) using **Python**, **Selenium**, and **BeautifulSoup**, and exports the data into an Excel file for analysis or tracking. This project is perfect for recruiters, job seekers, or anyone who wants real-time insights into the remote job market.

---

## Features

- ✅ Scrapes job titles, companies, tags, post dates, and links
- ✅ Parses JavaScript-loaded content using Selenium
- ✅ Converts Unix timestamps to readable date format
- ✅ Exports data to Excel (`.xlsx`)
- ✅ Clean, readable code with comments

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| `Python 3` | Programming Language |
| `Selenium` | Web Automation & Rendering JavaScript |
| `BeautifulSoup` | HTML Parsing |
| `pandas` | Data Cleaning & Excel Export |
| `Jupyter` / `Colab` | Development Environment |

---

## Sample Output

| Title              | Company     | Tags                  | Posted Date | Link                          |
|-------------------|-------------|------------------------|--------------|-------------------------------|
| Python Developer  | DevCompany  | Python, Backend, API   | 2025-06-16   | https://remoteok.com/xyz      |
| Full-Stack Engineer | WebTech     | JavaScript, React, AWS | 2025-06-15   | https://remoteok.com/abc      |

---

## Use Cases

- Job seekers tracking new remote jobs
- Recruiters monitoring competitor hiring
- Business owners collecting hiring trends
- Developers learning Selenium and web scraping

---

## Project Files

- `remoteok_scraper.ipynb` – Jupyter Notebook with full code
- `remoteok_all_jobs.xlsx` – Exported Excel file with scraped data
- `README.md` – This file

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/remoteok-webscraper.git
   cd remoteok-webscraper
