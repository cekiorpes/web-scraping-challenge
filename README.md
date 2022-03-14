# web-scraping-challenge
Using BeautifulSoup, Splinter, Pandas, MongoDB, and Flask to create a website with Mars information that will grab the most recent updates with a click of a button

## Mission to Mars
Data was scraped from four sites relating to the Mission to Mars: 
* [Mars News Site](https://redplanetscience.com/) - the latest news title and paragraph text 
* [JPL Mars Space Images](https://spaceimages-mars.com/)- the url of the featured image 
* [Mars Facts](https://galaxyfacts-mars.com/)- the Mars facts table
* [Mars Hemispheres](https://marshemispheres.com/)- the image urls and titles for the four hemispheres 

A Flask app script was created, with a landing page and a route that used the scrape function (from scrape_mars.py) to collect the above data, store it in MongoDB as a Python dictionary, and then pass the data into an HTML template to be displayed. 

![Application screenshot](Final_screenshot.png)
