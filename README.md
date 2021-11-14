# Congress
Congress Scraping

Senatescrape scrapes investment forms that a senator must file for each major investment. These forms are located on https://efdsearch.senate.gov/search/home/. 

The application uses selenium to check the inital agreement box and then passes the cookies and crsf tokens obtrained from the http response to python requests.

What is currently returned is a list of pandas dataframes for a given senator for a given period of time.
