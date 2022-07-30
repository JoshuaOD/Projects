# Project Overview

In this project, we'll perform sentiment analysis on stock news to give us the general thoughts and opinions on stocks we've selected.  

**Project Steps**

* Scraped website data using requests and BeautifulSoup.  
* Clean the data and get it ready for machine learning.
* Generated sentiment scores using NLP package `nltk`.
* Came to conclusions based on the end result of data scraping.

## Code

You can find the code for this project [here](https://github.com/JoshuaOD/Projects/tree/main/Sentiment%20Analysis).

File overview:

* `Sentiment Analysis of Stock News.ipynb` - Jupyter notebook that contains the end-to-end project.

# Local Setup

## Installation

To follow this project, please install the following locally:

* JupyerNotebook
* Python 3.8+
* Python packages
    * pandas
    * requests
    * BeautifulSoup
    * matplotlib
    * nltk.sentiment.vader
    
## Data

We'll be scraping [Finviz](https://finviz.com/) to get our data in the first part of this project.
