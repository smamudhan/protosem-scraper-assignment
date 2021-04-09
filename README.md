# Introduction
This is a very basic project built over three hours as an assignment for the ProtoSem program.  

It implements a basic webscraper that scrapes Flipkart for details; storing information in MongoDB and visualizing it on a webpage table. The entire application is run on python via Flask, which serves as a general use-case RESTful CRUD interface for MongoDB.

# Usage
To start the application, simply run the following commands:
```pip install requirements.txt```
```python api.py```
then visit [http://localhost:5000](http://localhost:5000)

> Fair warning, there are a lot of hardcoded DB connection strings, API endpoints etc. (especially in scraper.py); which will be refactored in the future to use `.env`.

The bare minimum to get it running right now (for the mentor) is to make sure your Chrome Webdriver Path is correctly configured in scraper.py. Other users may have to check MongoDB connection strings etc.

# More Information
Besides this README.md; the documentation for the API can be found by visiting `/docs` once the application is running. A postman collection is also available to download on there.  

Visiting the homepage (`/`) will display an introduction that details how the requirement of the assignment has been fulfilled; and link to the other docs.