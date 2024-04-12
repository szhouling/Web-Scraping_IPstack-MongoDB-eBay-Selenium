# IPStack & MongoDB

This repository contains my individual project that demonstrates hands-on experience with API integration, database programming using MongoDB, web scraping with Selenium, and data parsing with BeautifulSoup in Python. The project is divided into two main parts:

## Part 1: iPstack and MongoDB
- **MongoDB Setup and Connection**
  - Ensure MongoDB is installed and running locally.
  - Use a GUI tool to verify the operational status of MongoDB.

- **Database Programming**
  - Implemented a Python program to:
    - Connect to the local MongoDB instance.
    - Create a database named "msba."
    - Insert a document into the "ip_addresses" collection within the "msba" database.

- **Exploration of iPstack API**
  - Visited [ipstack.com](https://ipstack.com/) to understand and request a free API key.

- **API Integration and Data Retrieval**
  - Developed a Python program to make API calls for specific IP addresses.
  - Parsed JSON responses to extract and display city and zip code information.
  - Enhanced the program to store retrieved data in the MongoDB collection.

## Part 2: eBay + Selenium
- **Browser Automation with Selenium**
  - Automated browser access to [eBay](https://www.ebay.com/) using Selenium in Python.

- **Web Scraping and Data Parsing**
  - Conducted a search for "Cell Phones" on eBay.
  - Applied filters (e.g., Network: Unlocked, Brand: LG, etc.) to refine search results.
  - Saved the filtered search results page locally as an HTML file.

- **Data Extraction and Analysis**
  - Parsed the saved HTML file using BeautifulSoup in Python.
  - Extracted item details such as title, seller information, price, shipping, return policy, and bids.

The project includes well-commented Python scripts and relevant documentation to explain the code's functionality and decisions made during development.

---


