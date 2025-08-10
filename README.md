# Swedish-Student-Apartment-Scraper&Dta

## Description

**Version 202507** — This project is a web scraper designed to collect apartment rental listings from the Swedish rental market.

Currently, it focuses on **Stockholm**,File[STO-StudentHousing-dta-2307]covering multiple major rental platforms and housing providers, including:

- **SSSB** – Stockholm Studentbostäder  
- **SBS Norden** – Studentbostäder i Sverige  
- **Allihoop** – Coliving provider  
- **UNITY** – Serviced apartments and co-living  
- **Svenska Bostäder** – Public housing provider  
- **Stockholm University Housing Office** – University-managed student accommodation  

The scraper collects structured information such as apartment type, address, rent type (e.g., studio, corridor), size, rent price, available date, queue time, and floor level.

Future updates will expand coverage to **other Swedish cities** (e.g., Gothenburg, Malmö, Uppsala, Lund) and potentially other Nordic rental markets.

---
## Features

- Extracts apartment details such as:
  - Brand
  - Branch
  - Room Type
  - Rent type (e.g., Ensuite studio,corridor, 1 bedrooms or more rooms appartment)
  - Area
  - Rent
  - Moving-in date, Queue days, Floor info
- Uses `Selenium` to render dynamic content
- Certain appartment brand with a few branchs were extracted mannually
- Parses HTML using `BeautifulSoup`

---

## Notes

- The script `real_rental_web_crawler-SSSB.ipynb` is based on the **previous version** of the SSSB website and has **not yet been updated** to reflect the latest site structure.  
- Users may need to manually adjust selectors or scraping logic to match the current SSSB platform.

---

##  Requirements

Install the required libraries with:

```bash
pip install -r requirements.txt
```
Make sure you have ChromeDriver installed and accessible via PATH. Adjust your Selenium driver accordingly if using another browser.

---

## Citation

If you use this dataset or scraper in your work, we hope you clearly acknowledge the source.

**Authors:** Garbo He & Hona Zhu  

**Suggested citation:**

> He, Garbo & Zhu, Hona (2025). *Swedish-Apartment-Scraper: A web scraper for the Swedish rental market (Version 202507)*. Available at: https://github.com/GarboHe/Swedish-Apartment-Scraper

Any use of the data collected by this project must explicitly state the authors' names and the project title.
