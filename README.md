# Healthy_Calendar

<b>Description:</b>

This is a calendar app that provides the latest Covid information, daily exchange rate, and daily weather reminder to users. 
It differentiated itself from the general market with the pandemic data, finance info, and weather forecasting function all in one place. 
Users could not only receive relevant data efficiently, but could interact with that data and record down some of the key information to the calendar. 
This is a diary-like calendar with functions that offer users essential daily updates regarding the Covid trend and other relevant information.

<b>Objective:</b>

We want to help our users to live a healthy and convenient life. We help collect Covid, weather, and exchange rates information from several websites and put them on our app. Users no longer need to go through several apps or web pages to get the information they need. This app has them all in one place, and provides functions for users to interact with those data.

<b>Methodology:</b>

<p>The methods we used to obtain data includes scraping with BeautifulSoup, downloading csv from the web with pandas, and interpreting JSON API format using python requests module.
Variety of Kind of Data Sources</P>
<p>We collected data from different kind of places, including:</p>
A world weather forecasting website that includes the weather around the world. We scraped the data from the website through BeautifulSoup. The data contents include the time of each location, name of the location, and the weather description.
Several different files downloaded from the World Health Organization’s website. The data contents include the number of cases that are reported to the WHO, vaccination situation of the country, and each country’s current population information.
Lots of world exchange rates from Web API provided by Open Exchange Rate website. We interacted with the data using python’s library to extract the information we wanted.


