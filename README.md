# Ebook-Scraper

This script uses the requests library to send an HTTP GET request to the ebooks.com website's URL, and the BeautifulSoup library to parse the HTML of the response. It then searches the parsed HTML for the div element containing all of the book elements on the page, and uses a loop to iterate through these book elements, extracting the title and price of each book. The csv library is used to create a CSV writer object, which is used to write the extracted data to a CSV file, with each book being written as a row in the file and the title and price being written to the respective columns. The first row of the file is a header row with column titles.

