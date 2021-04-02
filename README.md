# deliveroo-web-scraper 
The aim of this project is to create a script that scrapes data from Deliveroo. Data is scraped on all restaurants that deliver to the postcode of choice. 

Deliveroo must deliver to your postcode in order for this to work and the postcode must be in the UK

## Questions: 
1. What cuisines are most popular near me? 
2. What is the quality of food in my vicinity?
3. How do the qualities of cuisines vary? 
4. Is there a relationship between popularity and quality?

To answer these questions and others, we scrape the following data.
## Data Fields:
1. Restaurant Name
2. Cuisines
3. Rating Score
4. Number of Reviews
5. Delivery Time
6. Delivery Cost
7. Distance 

The data is in a format where we can't just grab it. We need to search through the html of the page to find all the relevant information we want. When searching, there will several problems to solve.
## Problems to solve:
1. Given the site has an infinite scroll feature, how can we get a complete html file to search through?  
2. Within the html, how do we identify an individual restaurant?
3. Within the data on an individual restaurant, how can we pick out the pieces of data we want?
4. If the format is not consistent, can we possibly account for all the edge cases? 

Websites can constantly change, so the scraping techniques that work today may not work in the future.
## Limitations: 
1. The structure of the website may change, meaning the way to identify individual restaurants may stop working
2. The way that restaurant data is structured may change, meaning the way to identify restaurant data may stop working

To aid us along the way, we use some really helpful Python librarires. 
## Libraries:
1. Selenium - To simulate an instance of Chrome and scroll through the whole webpage
2. BeautifulSoup4 - To parse the html of the website
3. Time - To pause execution so that the instance of Chrome can load the webpage while scrolling
4. Numpy - Not directly used, but used by Pandas. Provides high-performance for array-like structures
5. Pandas - To create a data structure that is easy to manipulate and interpret for visualisation
7. NLTK - Natural Language Processing Library. We use a helpful tool to recognise sentences
8. Matplotlib - Not directly used, but used by Seaborn. Data visualisation library
9. Seaborn - A beautiful data visualisation library
