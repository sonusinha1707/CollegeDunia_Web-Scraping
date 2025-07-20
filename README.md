
# 📊 Collegedunia Colleges Scraper & Data Extractor

![Collegedunia Scraper Banner](https://github.com/sonusinha1707/CollegeDunia_Web-Scraping/blob/main/college_dunia_banner%20.png)

This project is a web scraping solution built using **Selenium** and **BeautifulSoup** to extract detailed data of **B.Sc. colleges listed on Collegedunia**. The data is automatically scrolled, parsed, and stored for further use in analytics, visualization, or machine learning applications.

---

### 🚀 Features

- Uses **Selenium WebDriver** to handle dynamic JavaScript loading and auto-scroll behavior.
- Parses the page content with **BeautifulSoup** to extract college details like:
  - College name
  - Location
  - Rating
  - Course fee
  - Placement data (if available)
- Supports deep page crawling with intelligent wait strategies.
- Can be extended to multiple course categories or other Collegedunia pages.

---

### 🧰 Technologies Used

- Python 3
- Selenium
- BeautifulSoup (bs4)
- WebDriverWait & Expected Conditions (EC)
- Regular Expressions (`re`)
- Time module (for dynamic wait control)

---

### 📦 Requirements

Install the dependencies with:

```bash
pip install selenium beautifulsoup4
```

Also, make sure you have a **ChromeDriver** installed and accessible via PATH. You can download it from:  
🔗 [https://sites.google.com/a/chromium.org/chromedriver](https://sites.google.com/a/chromium.org/chromedriver)

---

### 📂 Project Structure

```
Collegedunia-Project/
│
├── collegedunia.ipynb       # Main Jupyter Notebook
├── README.md                # Project overview and instructions
└── requirements.txt         # (Optional) Python package list
```

---

### 📌 How to Run

1. Open `collegedunia.ipynb` in Jupyter Notebook.
2. Ensure ChromeDriver is installed.
3. Run the cells step by step.
4. Extracted college data can be viewed or exported as needed.

---

### 📈 Possible Extensions

- Scrape other categories (Engineering, MBA, etc.)
- Export data to CSV or JSON
- Visualize rating distribution, location heatmaps, etc.
- Integrate with Pandas for further EDA

---

### 📜 License

This project is for educational purposes. Always ensure compliance with a website's [robots.txt](https://collegedunia.com/robots.txt) before scraping.
