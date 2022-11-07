# Dynamic-webpage (Twitter)-scrapping-using-Python 

Scraping Data From Twitter

I will use Selenium to login to Twitter and scrape data. Specifically, I will scrape posts using the hashtag #datascience as well as #dataviz.

Use the following website to login: https://twitter.com/login. If you attempt to use https://twitter.com, you will be faced with some challenging HTML code that is difficult to navigate.

When you enter your username, password, or a search term, no submit button is available to you. Instead, you will need to use Selenium's send_keys() function to submit for you.

How do you do this? Selenium can perform key presses from your keyboard virtually. For example, say you're me and your username is ZannatusSaba. So, if you would like Selenium to type in your Twitter username and submit the page for you (just like you would actually do), you would do something like this:

username_elem.send_keys('ZannatusSaba' + Keys.ENTER)

I will perform the following tasks in Python:

Navigate to Twitter and login 

Search for the hashtag #datascience 

Scrape data for two tweets by capturing the following:

Twitter name

username 

tweet text 

date 

Also will perform the following tasks:

Search for the hashtag #dataviz 

Scrape data for two tweets by capturing the following:

Twitter name 

username 

tweet text

date 

I will create a data frame to store your scraped data. Save the text data (name, username, tweet text, date) as a data frame with the following column names: 

name

username

tweet

date

At this point, the data frame should have 4 records: 2 for #datascience and 2 for #dataviz.

Export the data frame as a tab delimited file and name it twitter_<lastname>.txt where <lastname> is my last name

