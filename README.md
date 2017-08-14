# Project-T.O.M
TV or Movie?

## Goal
Project-T.O.M is designed to provide a cross streaming-platform recommendation to users for what to watch. The application gathers data from services such as Netflix, Hulu, and Amazon, to determine what a user would like to watch, TV or movie.

## Potential Streaming Services (Based on API accessibility)
* Netflix
* Hulu
* Amazon
* Youtube

## Functionality
* User can add credentials for different streaming accounts to T.O.M
* T.O.M will provide recommendations on what to watch on platform X based on:
  * What a user watches platform X and other platforms
  * What users watch on platform X and other platforms

* Recommendations for what to watch on platform X can be filtered by:
  * Genre
  * TV or Movie

* Users can login to their T.O.M profile using any of their associated platforms that they registered with in the first place.
* In their T.O.M profile, users can look at general recommendations on any platform, based on their viewing patterns
* T.O.M will also provide "Shows on other Platforms You Might Like" for each user within their profile page


## Frontend Details
* Currently, T.O.M will be delivered as a browser plugin that appears when a user logs into an associated streaming platform.

## Backend Details
* T.O.M will have a noSQL database structure through MongoDB
