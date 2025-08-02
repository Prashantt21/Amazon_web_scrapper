# Amazon_web_scrapper
This project is a simple Python-based web scraper that extracts product data from Amazon, specifically the product title and price. The scraper is designed to run periodically and can notify the user via email if the price drops below a certain threshold.
📦 Amazon Web Scraper Project
This project is a simple Python-based web scraper that extracts product data from Amazon, specifically the product title and price. The scraper is designed to run periodically and can notify the user via email if the price drops below a certain threshold.

🧰 Features
-Scrapes product title and price from a specified Amazon product page.
-Cleans and stores the data in a structured format.
-Automates daily scraping using time.sleep() and loops.
-Sends an email notification if the product price falls below a target value.
-Saves data to a .csv file for tracking over time.

📁 Project Structure
Libraries used: requests, bs4, smtplib, datetime, csv, and time
Core Components:
-requests + BeautifulSoup: For scraping product information.
-datetime: For timestamping the collected data.
-csv: For data logging.
-smtplib: For email alerts.
he script includes functionality to send an email when the product price goes below your defined target. Ensure you:

Enable less secure apps if using Gmail (or use an app password).

Replace placeholders with actual credentials.

🔄 Automation (Optional)
For continuous tracking, the script can be scheduled using:

time.sleep(86400) — Waits 24 hours between each run in a loop.

Or schedule the script with cron (Linux/macOS) or Task Scheduler (Windows).

🔒 Disclaimer
This script is for educational purposes. Amazon’s terms of service prohibit scraping in some contexts, and your IP may be blocked if you send too many requests. Consider using APIs or Amazon's affiliate program for production use.
