**README.md**
===============

Local Business Search
--------------------

A web application to search for local businesses based on various filters.

### Features

* Search for businesses by location and type
* Filter results by website availability, rating, verification status, phone number, and business status
* Display results in list, grid, table, compact, or detailed view
* Reset filters to default state

### Requirements

* RapidAPI key for Google Maps Geocoding API and Local Business Data API
* jQuery, Flowbite, AOS, and Toastr libraries

### Usage

1. Clone the repository and open the `index.html` file in a web browser.
2. Enter a location and business type in the search form.
3. Select filters as desired.
4. Click the "Search" button to display results.
5. Toggle between different views using the buttons above the results section.

### Configuration

* Replace `YOUR_RAPIDAPI_KEY` with your actual RapidAPI key in the `script` section of `index.html`.

**.env**
```makefile
RAPIDAPI_KEY=YOUR_RAPIDAPI_KEY
```
Replace `YOUR_RAPIDAPI_KEY` with your actual RapidAPI key.