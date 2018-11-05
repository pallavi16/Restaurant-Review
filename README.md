# Restaurant Reviews App Stage 1: Mobile Web Specialist

## Overview: Restaurant Review App Stage 1
Given an existing static webpage that lacks responsiveness, poor-design, the task is to convert it into fully responsive, 
mobile-ready, offline-first application. 
This repo contains the code for Stage 1 that modifies the webpage and provides great features listed below:
- Converting the provided page to use a responsive design which is accomplished using CSS 
(Bootstrap and other CSS frameworks have not been used).
- Responsive across various browsers such as Safari and Chrome.
- Provides accessibility features in the site HTML.
- Presence of ServiceWorker Script so as to make it work offline (when the internet connection is poor or not working.)


## Starter Code
The started code is forked/clone from Udacity for a restaurant reviews website. This repo has improved the site in mostly three main parts:

1. Responsive Design,
2. Accessibility and
3. Offline Use.

## Running/Testing your code on your machine:

To make this code work locally, a local server has been used to host this page. 
To run it from the terminal directly, python can be used as follows:
- Using Terminal enter into project directory
- In a terminal, check the version of Python you have: python -V.
- To run it with either of the Python versions:
  - If you have Python 2.x, spin up the server with python -m SimpleHTTPServer 3000 (or some other port, if port 8000 is already in use.)
  - For Python 3.x, you can use python -m http.server 3000.
- With your server running, visit the site: http://localhost:3000

To debug/test the code, Chrome DevTools serve the purpose in the Browser Inspector.

## API used:
Leaflet.js and Mapbox:
This repository uses leafletjs with Mapbox. mapboxToken: was replaced with a token from Mapbox-Access token in main.js and restaurant_info.js. It is free to use, and doesn't require any payment information.
