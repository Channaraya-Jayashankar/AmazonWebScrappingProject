# Amazon Web Scraper 

### A Python Web Scraping Project to Track Prices and Automate Alerts

---

## Overview

This project is a **web scraper** built using **Python** and **BeautifulSoup** to monitor product prices from **Amazon** and automate email alerts when prices drop below a defined threshold. It is designed for continuous data collection and can be customized to monitor different products.

As a Data Analyst, this project demonstrates my skills in **data extraction**, **web scraping**, and automating data-driven alerts, which are essential for making informed business decisions.

---

## Key Features

- **Web Scraping with BeautifulSoup**: Extracts product details such as title, price, and more from Amazon.
- **Data Storage**: Captures data in a structured format and stores it in a CSV file for further analysis.
- **Price Monitoring**: Continuously tracks price changes and updates the CSV file with real-time data.
- **Automated Email Alerts**: Sends an email notification when a product price drops below a certain threshold.
- **Scheduled Execution**: The script runs automatically at a defined interval (daily) to ensure fresh data is always captured.

---

## Technologies Used

- **Python**: Core language used for web scraping and data manipulation.
- **BeautifulSoup**: Library used to parse HTML and extract data from web pages.
- **Requests**: Used to handle HTTP requests to the web page.
- **CSV**: Stores scraped data in a CSV file for easy analysis.
- **smtplib**: Handles sending automated email notifications.
- **Pandas**: For data manipulation and visualization (optional).

---

## How It Works

1. **Scrape Product Information**: The script sends a request to the Amazon product page, retrieves the HTML content, and extracts key information such as title and price.

2. **Track Price Changes**: The scraper logs each price check and stores it in a CSV file with a timestamp.

3. **Automated Alerts**: If the price drops below the target price, the script automatically sends an email alert.

---

## Skills Demonstrated

- **Web Scraping**: Effectively extract structured data from complex web pages.
- **Data Automation**: Monitor and automate data collection over time.
- **Data Storage & Management**: Organize and store data for further analysis.
- **Alert Systems**: Automate alerts based on dynamic data.

---

## Future Enhancements

- Add functionality to scrape multiple products.
- Implement dashboards to visualize price trends over time using **Pandas** and **Matplotlib**.
- Improve error handling for dynamic web content and potential anti-scraping mechanisms.

---

