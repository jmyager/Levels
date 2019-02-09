# Levels (BassSavvy.com)
BassSavvy is a fullstack web application built for fishermen by fishermen. BassSavvy aggregates lake levels and bass fishing tournaments into one convenient place for fishermen to view.

## Technologies
- JavaScript
  - jQuery
  - Node.js
  - Express.js
- HTML5
- CSS3
- Bootstrap

## Overview and Accomplishments
Before BassSavvy, fishermen had to visit several different, very dated websites to access current lake level data in their area. Additionally, bass fishing tournaments are located on a wide variety of club and organization websites and BassSavvy aims to bring them all under one convenient roof. Because BassSavvy was created by a local fisherman who had identified the need, it has seen very high levels of growth since its launch in November of 2018. BassSavvy as of this writing boasts over 1750 total users and over 17,000 page views (February 2019). BassSavvy also currently serves 26 states in the U.S. with over 150 local lake levels.

## Features
* Users can select their state and see each lake available (
* Users can select each lake and see current levels, charts of the past week, and historical data of levels, flows, dates, and times.
* Users can view all available tournaments
* Users can filter and sort tournaments by organization, location, date, and more.

## Technical Details
* Lake level data is scattered across the internet, so data for the app is sourced from a variety of locations including USGS' API, ACE's A2W API, raw html scrape, and txt file scrapes.
* Once data is obtained from the source, it is formatted and displayed for the user in different views and tables.
* All states, lakes, and tournaments are dynamically created for the user based on their respective json file and values.

## Future Plans
* Implement a database to replace our current json data files
* Permanently store lake level data
* Add more lakes nationally
* Add more local tournaments
* Add fishing clubs/organizations pages
* User login feature
* Develop mobile application
* Tournament scheduling feature


## Demo
The test site with the most up to date code can be located here:
* [Github Repository](https://github.com/jmyager/Levels-Test)
* [Heroku hosted test site](https://guarded-plains-88685.herokuapp.com/)

## Live
The full site can be located here:
* [Github Repository](https://github.com/jmyager/Levels)
* [Live Website](http://www.basssavvy.com/)
