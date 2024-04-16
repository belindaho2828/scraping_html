# Summary #
This analysis analyzes the Mars news and Mars temperature facts sites by using the Browser object from Splinter to visit the websites and Beautiful Soup to scrape them.

There are two Jupyter Notebooks contained in the repostiory:

## Part 1 ##
Beautiful Soup was used to extract titles and previews of the news articles about Mars using the div tags and classes 'content_title' and 'article_teaser_body' respectively. I then used list comprehension to store the results in a list of dictionaries.

## Part 2 ##
Beautiful Soup was used to scrape the HTML table and find all rows contained in the table. The data pertained to the minimum temperature and atmospheric pressure observeed by the Curiosity rover. Other information scraped from the table, in addition to the minimum temperature and atmospheric pressure, were the id number of a single transmission from the rover (id), the date on Earth (terrestrial_date), the number of elapsed sols (Martian days) since Curiosity landed on Mars (sol), the solar longitude (ls), and the matian month (month). 

The results from the table scraping were stored in a list and converted to Pandas DataFrame for futher manipulation and plotting. 

# Tools Used #
BeautifulSoup, Splinter, Pandas, and Matplotlib

Please see the Jupyter notebooks for forther details and conclusions of the analysis. 