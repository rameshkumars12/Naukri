# Naukri
I had many questions about the data science field, like                                                                                                                           
  what are the skills we need to brush upon?                                                                                                                                     
  what are the different role's in the data science field?                                                                                                                       
  what are the some companies that are hiring the most?                                                                                                                           
  what are the education requirements needed?                                                                                                                                     
  which location has the highest job openings?                                                                                                                                   
  
  Instead of going through the internet for finding answers, I started to scrape naukri.com to get my answers using Beautifulsoup and Selenium.
  
# WebScraping
Web Scraping has many names, such as Web Harvesting, Screen Scraping, and others. It is a method of extracting large quantities of data from websites and storing it at a particular location (a local file in your computer or a database in a table).

In data science, to do anything, you need to have data at hand. To get that data, you’ll need to research the required sources, and web scraping helps you. Web scraping collects and categorizes all the required data in one accessible location. Researching with a single, convenient location is much more feasible and more comfortable than searching for everything one-by-one.

So I used BeautifulSoup, Request library and Selenium to scrape the data from naukri.com and got some answers for the questions i had.

  ## Request
    The requests module allows you to send HTTP requests using Python.The HTTP request returns a Response Object with all the response data (content, encoding, status, etc).

    Installinge Requests Module
    >pip install requests
    Importing Requests Library
    import requests
    source = requests.get(url)
    
 ## BeautifulSoup
    BeautifulSoup is used to parse the HTTP returned response object in a tree like structure so that we can extract required data from the response object easily.

    Installinge BeautifulSoup Module
    >pip install beautifulsoup4
    Importing BeautifulSoup
    from bs4 import BeautifulSoup as bs
    soup = bs(source.content)
    
I scraped 780 data science job listings from naukri.com and stored it in a csv. But the data's aren't clean to visualize So let's use pandas!!!

## Pandas
    Pandas is an python library which is used to clean messy data.
    
    The dataframe has been cleaned and arranged the data accordingly but what is the meaning of having a data in columns and rows,I don't have time to go throught the entire 780     rows to find the answers i need So i decided to create a dashboard to visualize it clearly using Tableau
    
    
### The Dashboard's Link has beed given below, Go and find your answers.

https://public.tableau.com/views/NaukriDataScienceJobAnalysis/Dashboard12?:language=en-US&:display_count=n&:origin=viz_share_link    
    
    
