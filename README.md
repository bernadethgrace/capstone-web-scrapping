# Capstone-Web-Scrapping
At this module, we want to learn how to extract information that we can get from a website or usually called Web Scrapping. We are using the data of Exchange Rate of USD to IDR from website: https://www.exchange-rates.org/history/IDR/USD/T. From this page, we can extract the information of Daily Exhange Rate data, and the date of exchange rate movement, that next will be analyzed and visualized to html format.

## Requirements
Actually to follow this module you only need to install beautifulsoup4 with pip install beautifulsoup4 and you are good to go. But here some libraries that needed to be installed first that I use at this module :

- beautifulSoup4
- pandas
- matplotlibs
- flask

## File Description
### 1. requirements.txt
Prepare your environment first, by installing the package needed in **requirements.txt** file, using this code:
```pip install -r requirements.txt```

### 2. Capstone Project - GAA.ipynb
Capstone Project - GAA.ipynb is a Jupyter Notebook file, that was filled with step by step of how to do webscrapping. You can follow those steps, until the data wrangling steps

### 3. app.py
After the webcrapping proccess has done, you can copy the process of webcrapping to this file, and then we can design the **Flask Dashboard** with the result of HTML file. The objectives is to share the analysis easier. This file required the files that was in **static** and **template** folder. You can design the html, using file **index.html**.

### 4. result.html
Here's the result that I got from webscrapping process and implement to flask dashboard, so the file is in html format.
