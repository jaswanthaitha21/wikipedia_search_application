# Wikipedia Search Application

A simple web application that allows users to search for articles on Wikipedia. The application fetches search results dynamically using the Wikipedia API and displays them in a user-friendly format.

## Features

- Search Functionality: Users can enter a keyword to search Wikipedia.
- Dynamic Results: Displays the search results dynamically using JavaScript.
- Loading Spinner: Shows a spinner while fetching data from the Wikipedia API.
- Responsive Design: The application is responsive and looks good on all devices.

## Technologies Used

- Frontend: HTML, CSS (Bootstrap)
- JavaScript: Fetch API for making asynchronous HTTP GET requests
- API: Wikipedia search API (`https://apis.ccbp.in/wiki-search`)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/jaswanthaitha21/Wikipedia.git
    cd Wikipedia
    ```

2. Open `jaswanthwikipedia.html` in your web browser.

## Usage

- Enter a keyword in the search input field and press "Enter".
- The application will display a list of search results from Wikipedia.


## Code Overview

- HTML: Contains the structure of the webpage, including a search input field and a container for displaying search results.
- CSS: Utilizes Bootstrap for styling and responsiveness.
- JavaScript:
  - `fetch`: Fetches data from the Wikipedia API.
  - `createAndAppendSearchResult()`: Creates and appends each search result dynamically.
  - `displayResults()`: Displays search results.
  - `searchWikipedia()`: Triggers the API call on pressing "Enter".
