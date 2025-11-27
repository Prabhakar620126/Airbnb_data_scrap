## 🏨 Airbnb Hotel/Room Data Web Scraper (Python)

This project scrapes real customer-visible Airbnb room/hotel listings using Python.
It uses requests, BeautifulSoup, and time to extract room prices, ratings, location, amenities, and more — just as a user sees them on Airbnb

## 📌 1. Project Overview
The goal of this project is to scrape Airbnb accommodation data across selected cities/locations. It automatically collects:
Room/Hotel listing titles
Price per night/2 neight 
Ratings
Number of reviews
Location
Host details
Listing URL

## 🎯 2. Problem Statement
Airbnb does not allow users to directly download hotel/room data.
Manual collection is slow and impossible at scale.
This scraper solves the problem by:

  ✔ Automatically visiting Airbnb search pages
  
  ✔ Extracting room/hotel details
  
  ✔ Handling multiple pages
  
  ✔ Saving data into a clean CSV
  
  ✔ Preserving a real-customer-like appearance by using delay

## 🧰 3. Libraries & Tools Used
  requests        → for HTTP GET requests  
  BeautifulSoup   → for HTML parsing  
  time            → for adding delays between requests  
  pandas/csv      → for storing scraped data  

## 🔁 4. Scraping Workflow

1️⃣ Send request to Airbnb search results

  (Example: https://www.airbnb.com/s/Delhi/homes)
2️⃣ Parse HTML with BeautifulSoup

  Extract listing cards
  
3️⃣ Collect fields:

  - Title
  - Room Type
  - Price
  - Rating
  - Reviews Count
  - Location
  - Amenities
  - 
4️⃣ Handle Pagination

  Scrapes multiple pages using updated URL parameters.
  
5️⃣ Add Delay

  time.sleep() ensures ethical scraping and prevents blocking
  
6️⃣ Store Data

## 📥 5. Download Scraped Result:
  ! [download](https://github.com/Prabhakar620126/Airbnb_data_scrap/blob/main/Hotel_Data_of_Different_Place.xlsx)
  
## 🖼 6. Screenshots (Before & After Scraping)
  🔍 Before Scraping — Airbnb Website
  
  <img width="1919" height="886" alt="image" src="https://github.com/user-attachments/assets/79e26124-53ef-4702-bb56-48ed1f237970" />

  📊 After Scraping — CSV Output

  <img width="1706" height="698" alt="image" src="https://github.com/user-attachments/assets/7c1286a3-a0db-4a1d-88cb-544b1c1c254b" />


## 📁 7. Python Code File
[scraper.py](https://github.com/Prabhakar620126/Airbnb_data_scrap/blob/main/Airbnb_hotel_data.ipynb )

## ⭐ 8. Features
| Feature                     | Description                      |
| --------------------------- | -------------------------------- |
| ✔ Real-customer appearance  | Scrapes only visible data        |
| ✔ Anti-blocking friendly    | Uses delays & simple headers     |
| ✔ Multi-page scraping       | Collects 100s of Airbnb listings |
| ✔ Clean & structured output | CSV file ready for analysis      |
| ✔ Customizable cities       | Delhi, Goa, Bengaluru, etc.      |


## ⚖️ 9. Ethical Disclaimer

✔ Only public data is scraped

✔ No login or authentication is bypassed

✔ Respectful delay is added

✔ For educational and research use only

Airbnb content belongs to Airbnb Inc.

Use responsibly.

## 🔮 10. Future Enhancements
  - Scrape room images
  - Scrape host verification data
  - Build Airbnb price prediction ML model
  - Create a Power BI Dashboard
  - Add Selenium support for dynamic pages
  - Add asynchronous scraping for faster result
  - Build Airbnb price prediction ML model
  - Create a Power BI Dashboard

# 🙌 Author  
**PRABHAKAR KUMAR SHAHI**  
📧 Email: prabhakar620126@gmail.com 
🔗 GitHub: https://github.com/Prabhakar620126
