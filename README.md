# webscraping
Scraping data from the web with Python

This is a web scraping app in Python, utilizing the modules requests, bs4, BeautifulSoup and pprint. The app can be run in command line, or any terminal. It uses the mentioned 
Python modules to scrape useful data from the first 2 pages of the site https://news.ycombinator.com/news (Hacker News). It gets the names, the links, and the number of votes
of all the news on those pages, which have above 99 votes. Then arranges these articles from most to least amount of votes. Finally, the information is presented in the terminal
(when the program is being run) as a list with separate dictionaries, each on a new line, containing as mentioned - the title, the link to, and the number of votes of the article.
So the user can chose which article to read, among the most popular and the most recent ones, by copying the link and pasting in a web browser. 
