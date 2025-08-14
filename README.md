# Swedish-Apartment-Analysis
 This project includes:
-A lightweight web scraper to extract apartment listings from a Swedish rental platform using Selenium and BeautifulSoup.
-A rent analysis file exported from PowerBI  



OBS:Make sure you have ChromeDriver installed and accessible via PATH. Adjust your Selenium driver accordingly if using another browser.

## Dataset 
SSSB[https://www.sssb.se/en/]



## Features

- Extracts apartment details such as:
  - Room type (e.g., studio,corridor)
  - Address
  - Rent type
  - Area, Living space, Rent
  - Moving-in date, Queue days, Floor info
- Uses `Selenium` to render dynamic content
- Parses HTML using `BeautifulSoup`



##  Requirements

Install the required libraries with:

```bash
pip install -r requirements.txt


