# Web Scraping
This repository contains a Jupyter Notebook with a script for web scraping data from the Mexican government's open data portal, located at https://datos.gob.mx/, using the Python libraries BeautifulSoup and Selenium. The script utilizes the capabilities of both libraries to navigate and extract the desired information from the website.

BeautifulSoup is used to parse and navigate the HTML structure of the website, allowing the script to target specific elements on the page and extract the relevant data. Selenium is used to interact with the website, simulating a web browser and allowing the script to handle dynamic content and interact with JavaScript elements on the page.

The script is able to extract information such as dataset titles, descriptions, and links, as well as statistics on the number of datasets and views. The extracted data is then cleaned and stored in a CSV file for further analysis.

The repository also includes detailed instructions on how to set up and run the script, as well as a sample of the scraped data in the CSV format.

## Make sure to run it with:
```
    python==3.7.3
    pandas==1.4.2
    selenium==4.7.2
    bs4==4.11.1
```

* Download: [**Chromedriver**](https://chromedriver.chromium.org/)

* Link: [**Mexican government's open data portal**](https://datos.gob.mx/)