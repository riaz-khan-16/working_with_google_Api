# Task 3: Google Maps Distance and Duration Calculator


## Overview
This Python script allows you to calculate the distance and duration between two locations using the Google Maps API. 
It sends a request to the Google Directions API and processes the received data to provide you with the distance and duration for a given journey.


## Explanation of the code:

I have imported the requests library to make HTTP requests.


I have defined a function get_distance_duration that takes the origin and destination addresses as input, constructs the API request URL, 
sends a GET request to the Google Directions API, and processes the response.

In the main part of the script, I have taken user input for the origin and destination addresses, call the get_distance_duration function, 
and print the distance and duration if results are found.

## Data processing approaches:

The script sends an HTTP GET request to the Google Directions API to obtain data. It checks the status code to ensure the request was successful.

It processes the received JSON data to extract the distance and duration information.

Error handling is included to handle cases where no results are found or if there is an issue with the request.

This script is a basic example of interacting with the Google Maps API and processing the data. 
