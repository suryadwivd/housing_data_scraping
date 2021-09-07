# Housing data extraction and training

Extracted various fields of information from housing website(MagicBricks) using web scraping. As the website requires redirecting to different url and scrolling and many other tasks, [Selenium](https://selenium-python.readthedocs.io/) is used in order to facilitate these tasks. There are 3 parameters required for the scroll function, they are driver, timeout (time to wait till next scroll) and number of times to scroll respectively.
Then the scraped data is utilized in Models.ipynb where it is processed and is used to train Linear Regression, Decision Tree and Random Forest Models.
