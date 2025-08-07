# Swedish-Apartment-Scraper

A lightweight web scraper to extract apartment listings from a Swedish rental platform using Selenium and BeautifulSoup. 
This project is part of a project which is dedicated to analyze Swedish rental market.


## Features

- Extracts apartment details such as:
  - Room type
  - Address
  - Rent type (e.g., student, youth)
  - Area, Living space, Rent
  - Moving-in date, Queue days, Floor info
- Uses `Selenium` to render dynamic content
- Parses HTML using `BeautifulSoup`

##  Requirements

Install the required libraries with:

```bash
pip install -r requirements.txt

Make sure you have ChromeDriver installed and accessible via PATH. Adjust your Selenium driver accordingly if using another browser.
