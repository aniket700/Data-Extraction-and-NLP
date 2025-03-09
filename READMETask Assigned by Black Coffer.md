
# Data-Extraction-and-NLP
This project aims to extract textual data articles from given URLs and perform text analysis to compute variables. The code is written in Jupyter Notebook for its flexibility compared to scripting.

Prerequisites
Before running the code, make sure to install the required packages by running the following command:

python3 install -r requirements.txt

Approach
The project follows the following steps:

input data: Read input data from input.xlsx using pandas.
Web Scraping: Use the requests module to get the raw HTML content from the URLs specified in the input file. Utilize the BeautifulSoup module to perform web scraping.
