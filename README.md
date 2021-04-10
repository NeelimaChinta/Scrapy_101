# Scrapy_101
**A simple guide to running your first sscrapy scraper.** </br>
Scrapy is a fast open source and collaborative web crawling framework written in Python, used to extract the data from web page with the help of selectors based on XPath. </br>

### Prerequisites 
You should have a basic understanding of Computer Programming terminologies and Python. A basic understanding of XPath is a plus. </br>

### Website used to scrape
I chose http://quotes.toscrape.com/ to scrape. It is a website that displays various quotes based on different tags and also include the author's name. </br>

### Installing Scrapy and creating a new project
To install scrapy run the following command on your terminal or command prompt: </br>
```
Pip install scrapy
```
This will install scrapy. </br>
**Note:**  If you're on windows, make sure to install  **PyWin32**. </br>

To create your first project, run the following command: </br>
```
Scrapy startproject quotetutorial
```
Here, quotetutorial is the name given to my project.
The above command will create a directory with name quotetutorial and it will contain the following structure −
```
quotetutorial/
scrapy.cfg            # deploy configuration file
first_scrapy/         # project's Python module, you'll import your code from here
__init__.py
items.py              # project items file
pipelines.py          # project pipelines file
settings.py           # project settings file
spiders/              # a directory where you'll later put your spiders
__init__.py
```





