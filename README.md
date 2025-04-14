
# 🏠 Zillow Rental Scraper and Auto-Submitter 🧠

This Python project scrapes rental property data—addresses, prices, and links—from a Zillow-like listing website and automatically fills them into a Google Form using Selenium.

## 🚀 Features

- Scrapes rental data (price, location, and listing link) from a Zillow clone.
- Cleans and processes scraped information using BeautifulSoup.
- Automates form submissions via Selenium to collect data into Google Sheets.
- Fully automated workflow to extract and organize rental listings efficiently.

## 📸 Demo

<img src = "https://github.com/user-attachments/assets/f21f5280-75a5-4ccb-959c-62baef6f3391" width = "800">

> Automatically filling out Google Forms with real-time scraped data.

## 🧰 Tech Stack

- `Python`
- `BeautifulSoup`
- `Requests`
- `Selenium`
- `Google Forms`

## 📄 Requirements

Install the necessary Python packages using:

```bash
pip install beautifulsoup4==4.12.2 requests==2.31.0 selenium==4.15.1
```

Also, ensure you have Chrome installed and the **ChromeDriver** version matches your browser version.  
Download it here: [https://chromedriver.chromium.org/downloads](https://chromedriver.chromium.org/downloads)

## 📂 Project Structure

```
main.py             # Main script to scrape data and submit the form
README.md           # Project overview and instructions
```

## 🔗 Links

- **Google Form**: [Submit Rental Listings](https://docs.google.com/forms/d/e/1FAIpQLSciycdmVXPeo1Y0Cu1NLDAafQty2eai9vfKFbB1BDATshe0fg/viewform?usp=header)
- **Response Sheet**: [View Collected Data](https://docs.google.com/spreadsheets/d/1Zr1PZhcAyc8YdhP5opfqdpxrQ9BCCzxvNuzVJXVpzRs/edit?resourcekey=&gid=623921912)

## 🧪 How to Use

1. Clone this repo:
    ```bash
    git clone https://github.com/your-username/zillow-scraper.git
    cd zillow-scraper
    ```

2. Run the script:
    ```bash
    python main.py
    ```

3. Watch your Google Form fill itself!

## 📌 Notes

- This script is for **educational purposes** and mimics scraping publicly available data from a test Zillow-like site.
- Update the XPath in `main.py` if your Google Form structure changes.

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

📬 Feel free to reach out for feedback or collaboration!
