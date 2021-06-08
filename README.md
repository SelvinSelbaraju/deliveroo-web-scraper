# Welcome to my Deliveroo Web Scraper and Data Analysis Notebook!

Imagine we work at Deliveroo. We have lots of data on all of our restaurants and using this data, you want to gain some insight into how the company could increase order value and/or order frequency. 

For example, we may want to look at what cuisines are most / least common on the platform for certain postcodes. If a cuisine is undersupplied in the area, we could set up dark kitchens serving that cuisine or try to partner up with more restaurants of that cuisine.

Another important question is how relevant restaurant reviews are. Do restaurants with a better rating get more orders? Or are the ratings on the platform so inflated that the difference between a 4.1 and a 4.5 is irrelevant? 

### But we do not work at Deliveroo...

Unfortunately, we do not have the data. Therefore, we will first need to scrape it from Deliveroo's website and clean it up before analysing it. Given this, it will take too long to get this data for all postcodes in a city. Therefore, we will look at the analysis for one postcode for now.   

The aim of this project is to be able to scrape key information on all the restaurants that are active at the time of scraping. The data then needs to be cleaned so it can be analysed. Be wary that if you scrape the data in the morning, lots of restaurants may be closed. As a result, they may not be captured when scraping. Therefore, I recommend scraping in the evening for the best results (unless you are specifically interested in the websites serving at a certain time of day). 

I wanted to make this as accessible for beginners as possible, so I've outlined all of my steps. I am by no means an expert, and feedback is always much appreciated!

In order to achieve our aim, we will need the following restaurant data: 
1. Restaurant Name
2. Restaurant Rank (where it is positioned on the website)
3. Cuisines
4. Rating (number of ratings and score)
5. Distance
6. Delivery Cost
7. Delivery Time

Using this information, we can perform some data visualisations and simple analysis. For example, we may want to see what is the best cuisine in a postcode, or see if there is a relationship between the rating score and order frequency. These questions are important to understand as they drive the number of orders Deliveroo gets, and thus their revenues.

In addition, it is also interesting to look at the price different restaurants charge for the same dish (I use Egg Fried Rice as an example). If some restaurants are undercharging, they could be told to slightly raise their price. Assuming this price increase doesn't affect their number of orders for Egg Fried Rice, order value will go up and thus Deliveroo's revenues would rise.  

### This only works for the UK at the moment

# Feedback is always much appreciated! I am very keen on how to both improve this notebook and all my Data Science / Programming skills!
