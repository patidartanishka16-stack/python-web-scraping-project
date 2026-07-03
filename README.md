# 🌐 Python Web Scraping - Quote Scraper

A simple Python web scraping project that extracts quotes and authors from the **Quotes to Scrape** website using **Requests** and **BeautifulSoup**, then saves the data into a CSV file.

## 🚀 Features

- Fetches webpage using `requests`
- Parses HTML using `BeautifulSoup`
- Extracts:
  - Quote
  - Author
- Saves data to `quotes.csv`
- Beginner-friendly project

## 🛠 Technologies Used

- Python 3
- Requests
- BeautifulSoup4
- CSV Module

## 📂 Project Structure

```
Python-Web-Scraping/
│
├── quote_scraper.py
├── quotes.csv
└── README.md
```

## ▶️ How to Run

1. Clone the repository

```bash
git clone <your-repository-link>
```

2. Install dependencies

```bash
pip install requests beautifulsoup4
```

3. Run the program

```bash
python quote_scraper.py
```

## 📄 Output

The program creates a file named:

```
quotes.csv
```

which contains:

| Quote | Author |
|--------|---------|
| Quote 1 | Author 1 |
| Quote 2 | Author 2 |

## 📚 Concepts Practiced

- Web Scraping
- HTML Parsing
- BeautifulSoup
- CSS Selectors
- find()
- find_all()
- zip()
- CSV File Handling

## 👩‍💻 Author

**Tanishka Patidar**

---

⭐ This project was built as part of my Python learning journey.
