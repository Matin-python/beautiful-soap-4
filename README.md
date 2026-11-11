# Web Scraper

A simple Python web scraping project that uses **Requests** and **BeautifulSoup** to retrieve, parse, and extract information from web pages.

## Overview

This project demonstrates the fundamentals of web scraping with Python. It sends HTTP requests to websites, retrieves their HTML content, and extracts specific information using HTML tags and CSS classes.

The project provides a starting point for collecting and processing data from websites.

## Features

- Retrieve webpage content using HTTP GET requests.
- Parse HTML documents using BeautifulSoup.
- Find HTML elements by their tags and CSS classes.
- Extract text from selected webpage elements.
- Display extracted information in the terminal or Jupyter Notebook.

## Technologies

- **Python** – Main programming language.
- **Requests** – Sending HTTP requests and retrieving webpage content.
- **BeautifulSoup4** – Parsing HTML and extracting information.
- **Jupyter Notebook** – Writing and executing the code.

## How It Works

1. Specify the URL of the target webpage.
2. Send an HTTP GET request using Requests.
3. Retrieve the HTML content of the webpage.
4. Parse the HTML using BeautifulSoup.
5. Find specific HTML elements using tags and CSS classes.
6. Extract and display the selected information.

## Installation

Install the required libraries:

```bash
pip install requests beautifulsoup4
```

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/Matin-python/Web-Scraper.git
```

2. Navigate to the project directory:

```bash
cd Web-Scraper
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebook cells to retrieve and extract information from the target webpage.

## Limitations

- Extracted information depends on the HTML structure of the target website.
- Some websites load content dynamically using JavaScript.
- Website structures and CSS classes may change over time.
- Some websites restrict automated requests or require additional authentication.

## Future Improvements

- Extract structured information such as titles, prices, and descriptions.
- Store extracted data in Pandas DataFrames.
- Export collected information to CSV or Excel files.
- Implement error handling for failed HTTP requests.
- Support more flexible data extraction and filtering.


## Contributing

Contributions are welcome.

You can improve the feature engineering, add new classification algorithms, improve the evaluation process, or add additional visualizations to the project.


## License

This project is licensed under the **MIT License**.

See the `LICENSE` file for more information.


## Author

**Mohammad Reza Bakhshandeh**

Electrical Engineering (Electronics) Graduate

Interested in Python Development, Machine Learning, Computer Vision, Artificial Intelligence, and Data Science.
