# Mission-to-Mars
## Project Overview
Gathering news updates on Mars missions and performing exploratory analysis of Mars climate data for SpaceForward--an aerospace company doing research about resource extraction from nearby planets--through scraping of public websites to create a usable database for the company's future projects.
## Resources
  - Data Sources: "https://redplanetscience.com/"; "https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html"
  - Software: Python v3.7.13, Jupyter Notebook v6.4.8, Splinter v0.14.0, Webdriver_Manager v3.8.5, BeautifulSoup v4.11.1
## Summary
### Deliverable 1
Utilizing Splinter and BeautifulSoup to stay up-to-date on Mars' current events, we gathered the titles and intro paragraphs of news articles from [News - NASA Mars Exploration](https://redplanetscience.com/). Though the code we wrote only scrapes the first 15 articles that appear on the news site's landing page, it could be augmented to scrape a larger number of articles--such as 50--by instructing Splinter to click the 'Next' button in the for loop as many times as necessary to gather the desired number of article titles and intro paragraphs before exporting to our databases JSON files.

### Deliverable 2
Our Mars' climate data was gathered by the [Curiosity rover mission](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html). It contains transmitted observations of 1867 sols (Martian days), with multiple results from each of Mars' 12 months. On average--at the location of Curiosity--Mars' coldest month is the 3<sup>rd</sup> month (-83.3°C), and Mars' hottest month is the 8<sup>th</sup> month (-68.3°C).

![Avg_Temp_by_Month](https://github.com/Jay-ni13/Mission-to-Mars/blob/main/Images/avg_temp_by_month.png)

Mars's average atmospheric pressure--at the location of Curiosity--is lowest in the 6<sup>th</sup> month (745.1), and highest in the 9<sup>th</sup> month (913.3).

![Avg_Pressure_by_Month](https://github.com/Jay-ni13/Mission-to-Mars/blob/main/Images/avg_pressure_by_month.png)

To discover how many Earth days exist in a Martian year, we utilized the solar longitude data to determine how many Earth days passed during Mars' travel through its 359 solar longitude coordinate points; the answer is 686 Earth days.

We also charted Mars' daily minimum temperature on a line graph to visualize how Mars' weather varied from year to year during Curiosity's mission. Barring several outliers, Mars' temperature appears very cyclical and invariate each year.

![Minimun_Temp_by_Day](https://github.com/Jay-ni13/Mission-to-Mars/blob/main/Images/minimum_temp_by_day.png)
