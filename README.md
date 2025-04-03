# Word Frequency Analyzer

This Python project combines web scraping and text analysis to extract and analyze word frequencies from any webpage. Using the requests library for HTTP requests, BeautifulSoup for HTML parsing, and click for command-line interaction, the script identifies the most frequently occurring words on a webpage based on user-defined minimum word length.

# Features:
* Web Scraping: Extracts all text content from a given URL using requests and BeautifulSoup.
* Word Frequency Analysis: Counts occurrences of words while filtering by user-specified minimum length.
* Command-Line Interface: Provides a simple CLI using click for easy input of URL and word length parameters.
* Top Words Display: Outputs the top 10 most frequent words in descending order.

# Requirements:
* Python 3.x
* Libraries: click, requests, beautifulsoup4

# How to Use:
Install dependencies:
```
pip install click 
pip install requests
pip install beautifulsoup4
```
Run the script:
```
python3 word_extractor.py
```
Flags:
* --url https://google.com
* --help

Example:
```
python3 word_extractor.py
```
```
Web URL:  https://google.com
('GoogleSearch', 1)
('Images', 1)
('Maps', 1)
('Play', 1)
('YouTube', 1)
('News', 1)
('Gmail', 1)
('Drive', 1)
('More', 1)
('Web', 1)
```
