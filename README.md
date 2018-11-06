# Restaurant Reviews App Part 1

## Overview: Restaurant Review App
A fully responsive, mobile-ready, offline-first application that allows the user to view restaurant-listings, to filter them out based on its location and cuisines.
This repo contains the code that modifies the webpage and provides great features listed below:
- Making a responsive page which is accomplished using CSS  (Bootstrap and other CSS frameworks have not been used).
- Responsive across various browsers such as Safari and Chrome.
- Provides accessibility features in the site HTML.
- Presence of ServiceWorker Script so as to make it work offline (when the internet connection is poor or not working.)


Live demo: https://pallavi16.github.io/Restaurant-Review/ 

## Running/Testing your code on your machine:

To make this code work locally, a local server has been used to host this page.
To get this code on your machine, use one of the 2 options below:
1. Option #1: Download the zip file from the main repo page.
2. Option #2: Use command line- "git clone https://github.com/pallavi16/Restaurant-Review.git" 

Now, to run it from the terminal directly, python if required:
- Using Terminal enter into project directory
- In the terminal, check the version of Python you have: ## python -V.
- To run it with either of the Python versions:
  - If you have Python 2.x, spin up the server with "python -m SimpleHTTPServer 3000" (or some other port, if port 3000 is already in use.)
  - For Python 3.x, you can use python -m http.server 3000.
- With your server running, visit the site: http://localhost:3000

To debug/test the code, Chrome DevTools serve the purpose in the Browser Inspector.

## API used:
Leaflet.js and Mapbox:
This repository uses leafletjs with Mapbox. mapboxToken: was replaced with a token from Mapbox-Access token in main.js and restaurant_info.js. It is free to use, and doesn't require any payment information.
