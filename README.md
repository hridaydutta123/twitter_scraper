## Twitter webscraper for specific pages
  
#### Python web scraper using Selenium and BeautifulSoup modules to extract text from various Twitter pages.
  
The program uses *<a href="http://www.seleniumhq.org/" target="_blank">Selenium</a>* (and ChromeDriver) to automate user behaviour within a browser session to load a specific Twitter page (no login) and load data from dynamic scrolling. Once the pages are rendered the HTML is extracted and sieved through *<a href="http://www.crummy.com/software/BeautifulSoup/bs4/doc/" target="_blank">BeautifulSoup</a>*. Note: it will continue scraping until 1) end of feed is reached, 2) manual interrupt by killing the connection.
  
This program will extract the following and output to a CSV file with punctuation and other non-text characters removed:
- full tweet text from each Twitter page
- date
- header
- url
- user name 
- popularity metrics (string containing retweets/favourites)
- like_fave: integer value for number of times 'favorited'
- share_rtwt: integer value for number of times 'retweeted'


This program can also check whether the twitter url account is having the warning:
> Caution: This account is temporarily restricted


![Twitter](https://g.twimg.com/Twitter_logo_blue.png)

![Selenium Browser Automation](http://www.seleniumhq.org/images/big-logo.png)
