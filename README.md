# WebCrawler

A simple web crawler built using Node.js, Axios, and Cheerio.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/WebCrawler.git
    cd WebCrawler
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

## Usage

To start the web crawler, run the following command:

```bash
node index.js
```

The crawler will start from the URL specified in the `startUrl` variable and will crawl up to the depth specified in the `maxDepth` variable. The results will be saved in `results.json`.


## Configuration

You can configure the following variables in the `index.js` file:
* `startUrl`: The URL to start crawling from.
* `maxDepth`: The maximum depth to crawl.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
