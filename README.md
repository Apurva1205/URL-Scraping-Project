# URL-Scraping-Project
Task 1:
The task 1 involves scraping information from Amazon India's product listing pages for the search term "bags". 
The information to be scraped includes the Product URL, Product Name, Product Price, Rating, and Number of Reviews. At least 20 pages of product listings are to be scraped. The information can be used for data analysis and market research purposes. This task requires a good understanding of web scraping techniques and the ability to extract information from HTML pages.

Task 2:
This code uses the Python Requests library and BeautifulSoup library to scrape information about products on Amazon India. It starts by sending a GET request to a URL that displays a list of bag products on the site. The HTML content of the page is then parsed using BeautifulSoup and the relevant information is extracted using various find and find_all methods.

The code defines a function called "scrape_product_info" which takes a product URL as an input and returns information about the product such as its description, ASIN number, product description, and manufacturer. This function is called in the main part of the code where it loops through each product container on the page, extracts information about the product URL, name, price, rating, number of reviews and calls the scrape_product_info function to get information about the product.

The extracted information is then stored in a dictionary object and the code continues to loop through all the products on the page until all the information is collected. The final output is a collection of dictionaries containing information about each product.
