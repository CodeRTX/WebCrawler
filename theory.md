Summary: 

The script starts by loading any existing results from a JSON file. It then defines a recursive `crawl` function that fetches a web page, extracts links, and recursively crawls those links up to a specified depth. A delay of 1 second is added between requests to avoid overwhelming the server. The results are saved to a JSON file after the crawling is complete. The script begins crawling from a specified start URL with a maximum depth of 2.

Modules Used: 

`axios`:
A promise-based HTTP client for making asynchronous HTTP requests.
Used to fetch the HTML content of web pages.

`cheerio`:
A fast, flexible, and lean implementation of core jQuery designed specifically for the server.
Used to parse the HTML and extract links from the fetched pages.

`fs`:
Provides an API for interacting with the file system.
Used to read existing results from a JSON file and write the updated results back to the file.
