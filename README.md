# Mission-to-Mars
## Project Overview
Gathering news updates on Mars missions and performing exploratory analysis of Mars climate data for SpaceForward--an aerospace company doing research about resource extraction from nearby planets--through scraping of public websites to create a usable database for the company's future projects.
## Resources
  - Data Sources: "https://redplanetscience.com/"; "https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html"
  - Software: Python v3.7.13, Jupyter Notebook v6.4.8, Splinter v0.14.0, Webdriver_Manager v3.8.5, BeautifulSoup v4.11.1
## Summary
### Deliverable 1
Utilizing Splinter and BeautifulSoup, we gathered the titles and intro paragraphs of news articles from [NASA's MARS Planet Science Exploration Program](https://redplanetscience.com/). Though the code we wrote only scrapes the first 15 articles that appear on the news site's landing page, it could be augmented to scrape a larger number of articles--such as 50--by instructing Splinter to click the 'Next' button in the for loop as many times as necessary to gather the desired number of article titles and intro paragraphs.

### Deliverable 2

![Avg_Temp_by_Month](https://github.com/Jay-ni13/Mission-to-Mars/blob/main/Images/avg_temp_by_month.png)

![Avg_Pressure_by_Month](https://github.com/Jay-ni13/Mission-to-Mars/blob/main/Images/avg_pressure_by_month.png)

![Minimun_Temp_by_Day](https://github.com/Jay-ni13/Mission-to-Mars/blob/main/Images/minimum_temp_by_day.png)
