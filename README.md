# Mission-to-Mars
Web Scraping with HTML/CSS
## Overview
In this project we are going to build a web application that scrapes various websites for data related to the Mission to Mars using BeautifulSoup and Splinter, store the scraped data on a Mongo database, and finally display the information in a single HTML page. 

## Resources
Software: VS Code 1.68.1   Python 3.7.6   Jupyter Notebook 6.4.8

## Results
### Step 1 – Scraping
#### NASA Mars News
-	Scrape the NASA Mars News site and collect the latest news' title and paragraph text.
#### JPL Space Images Featured Image
-	Visit JPL Space Images webpage and navigate through it to find a full-size image, and then extract a link based on its location on the page.
#### Mars Facts
-	Scrape the table from Mars Facts webpage and convert the data to a HTML table string.
#### Hemispheres
-	Scrape full-resolution images of Mars’s hemispheres and the titles of those images using BeautifulSoup and Splinter.
-	Add the code we created above to “scraping.py” file, update the Mongo database, and modify the “index.html” file so the webpage contains all the information we collected in this module as well as the full-resolution image and title for each hemisphere image.
![scrap script](https://user-images.githubusercontent.com/107179765/185067461-1af1287f-aa2a-4582-af7b-1ca1e3b9d27e.png)
### Step 2 - MongoDB and Flask Application
-	Set up a MongoDB to hold the data that gets scraped, use Flask to create a web app, update the scraping code to include functions and error handling, integrate MongoDB into the web app.
### Step 3 – Customize the Appearance
-	Create a new HTML page that displays all of the information that was scraped from the URLs above.
-	Update the web app to make it mobile-responsive, and add Bootstrap 3 components to make it stand out.
![web scrap](https://user-images.githubusercontent.com/107179765/185071100-d442cc86-0623-462f-b709-59dc90289a10.png)

## Summary
Everything we've been working on scraping has been collected into one location and presented in a clear and pleasing way. For a successful scrape, we’ll use Chrome Developer Tools to identify HTML components, BeautifulSoup and Splinter to automate the scrape, Mongo to store the data, and Flask to display data. Web scraping is a method of gaining data from different sources quickly instead of visiting each website yourself and then manually extracting the data.
