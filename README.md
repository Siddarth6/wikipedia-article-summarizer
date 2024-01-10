# Wikipedia Article Summarizer
## Overview
The Wikipedia Article Summarizer is a Python project that utilizes Selenium for web automation, Natural Language Processing (NLP) for text analysis, and tkinter for creating a simple graphical user interface (GUI). The application allows users to input a Wikipedia article link or keyword, fetches the article content, and provides a summary of the first three paragraphs.

## Features
- **Web Scraping**: Utilizes Selenium and BeautifulSoup to scrape content from Wikipedia articles.
- **Natural Language Processing**: Analyzes the scraped text to generate a summary of the article.
- **Graphical User Interface (GUI)**: Created with tkinter for a user-friendly experience.
- **Link or Keyword Input**: Accepts both Wikipedia article links and keywords for searching.

## Prerequisites
- Jupyter Notebook
- Selenium
- GeckoDriver
- BeautifulSoup
- Natural Language Toolkil(nltk)

## Installation
1. Install required python dependencies:
   ``` cmd
   pip install selenium webdriver-manager beautifulsoup4 nltk
   ```
2. Clone the repostory:
   ``` cmd
   clone git https://github.com/Siddarth6/wikipedia-article-summarizer.git
   ```

## Usage
1. Run python script:
   ``` cmd
   jupyter nbconvert --execute --to notebook --inplace WikipediaArticleSummarizer.ipynb
   ```
2. Enter a Wikipedia article link or keyword in the GUI.
3. Click the "Search" button to fetch and display the article summary.

## Screenshots
![Screenshot (9)](https://github.com/Siddarth6/wikipedia-article-summarizer/assets/103209785/1294f787-3bf0-45fa-a002-076f2e45e390)

![Screenshot (10)](https://github.com/Siddarth6/wikipedia-article-summarizer/assets/103209785/abab5f02-3930-4fd3-909f-765da7c05fff)

![Screenshot (11)](https://github.com/Siddarth6/wikipedia-article-summarizer/assets/103209785/7aa40c86-a097-4502-bc43-a53cac93f3f2)




   
