# UFOS
Module 11


## Overview of Analysis:

After creating Dana's UFO Sightings webpage with a filter search for the date, we have gone back and added 4 additional options in the filter search.  This will allow a more in-depth analysis of UFO sightings by allowing users to filter the search for the added criteria.

The additional filters added are for city, state, country and shape.


## Resources:

Software: 
Jupyter Notebook, Anaconda 4.10.1, Python 3.7.6, Visual Studio Code 1.56.0
 
Code:<br/> 	
[index.html](index.html) <br/>
[style.css](static/css/style.css) <br/>
[app.js](static/js/app.js) <br/>
		
Resources:<br/>	
[data.js](static/js/data.js)

Images:<br/>	
[images](static)			


## Webpage Use:

Below we are providing a walk-through of how to use the webpage.  We start off by selecting a date of 1/7/2010.  This returns us 7 entries in the chart over 4 state.<br/>
![date_search.png](static/images/date_search.png) <br/>

To narrow our search even further we selected the state of Massachusetts (ma).  We have filtered our results down to 3 entries in the chart.<br/>
![state_search.png](static/images/state_search.png) <br/>

We decided that we wanted to get all the filtered entries that had a "light" shape at the sightings in Massachusetts.  Our chart now displays only 2 entires and has become easier to interpret.<br/> 
![shape_search.png](static/images/shape_search.png) <br/>

This is a sample image of using the city filter to collect all the entries for "el cajon" in the table.<br/>
![city_search.png](static/images/city_search.png) <br/>

This is a sample image of using the country filter to collect all the entries for "us" in the table. <br/>
![country_search.png](static/images/country_search.png) <br/>


## Summary:

I have found the webpage has a few flaws in it.  To reset the table you have to scroll to the top of the site and click on the UFO Sightings at the top left of the page or the browsers refresh button.  For the filter search to work properly you have to use the exact term or it will return zero results in the table.  And the last issue is that the only country currently in the search data is the United States of America (us).

To improve the flow and function of the webpage I would have a reset/refresh button for the filter search located near the filter search.  I would add another filter option to search based on the duration category of the table, maybe use that until more countries are added to the data.  I also believe that the option to search between mulitple dates would further enhance the abilities of the webpage.  Lastly, the ability to serach not using exact names would also help imporve the webpage.