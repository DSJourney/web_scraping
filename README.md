# Web Scraping

Information: Here I add some of the web scraping notebooks I have developed in the past using Selenium, requests, and BeautifulSoup.

**1. Web scraping financial data from Macrotrends.net - My first scraper**

**libraries:** pandas, requests, BeautifulSoup, openpyxl, re, json

[Scraper Notebook](https://nbviewer.jupyter.org/github/DSJourney/web_scraping/blob/master/Financial%20Data%20-%20Beautiful%20Soup/MacroTrends_Data_Collection.ipynb)

The first web scraper I created was a simple bot that extracted information from the website [macrotrends.net](https://www.macrotrends.net/) my final goal was to use the data to create a Tableau visualization (which I have not finished yet...)


<p align="center"><img src=https://dcassetcdn.com/design_img/2932562/29696/29696_16155151_2932562_badd54c6_image.jpg width="300"></p>

<br>

**2. Scraping Jobs from Indeed.com - Stepping up the game** 

**libraries:** selenium, pandas, numpy, os, scikit-learn, matplotlib, pickle

[Scraper NoteBook](https://nbviewer.jupyter.org/github/DSJourney/web_scraping/blob/master/Job%20scraping%20-%20Selenium/scraper.ipynb) <br>
[Analysis Notebook](https://nbviewer.jupyter.org/github/DSJourney/web_scraping/blob/master/Job%20scraping%20-%20Selenium/analysis.ipynb)

This is where I started using Selenium. I created a bot that goes to [indeed.com](indeed.com) and extracts the jobs according to whatever keywords your specify. I also included an analysis of the keywords to use for each position (business, data analyst, data scientist, machine learning engineer, software engineer).

<br>

<p align="center"><img src=https://upload.wikimedia.org/wikipedia/commons/thumb/f/fc/Indeed_logo.svg/1200px-Indeed_logo.svg.png width="300"></p>
