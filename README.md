# UFO Sightings

## Overview of the analysis
* To build a webpage and dynamic table for UFO sightings at different locations using Javascript, HTML/CSS and Bootstrap for a client.
* To provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. 
* In addition to the date, add table filters for the city, state, country, and shape.

### Obejective
* Build a table using data stored in a JavaScript array. 
* Create filters to make this table fully dynamic, meaning that it will react to user input.
* Place the table into an HTML file for easy viewing.
* Customize the webpage using Bootstrap.
* Equip the table with several fully functional filters that will allow users to interact with our visualizations. 

## Results
* A dynamic webpage created for UFO sightings:

<img width="1440" alt="Screen Shot 2022-11-14 at 6 59 08 PM" src="https://user-images.githubusercontent.com/111387025/201672347-edf41137-7cee-47c2-9f15-6dbd9a9c01b9.png">

* There are multiple search filters available on the webpage, as shown in the image:

<img width="1434" alt="Screen Shot 2022-11-14 at 7 01 41 PM" src="https://user-images.githubusercontent.com/111387025/201672930-445558b9-14c8-4b84-92b5-f42a02d3f17c.png">

* The webpage showing the results after the filtered search for date - '1/1/2010', city - 'el cajon', state - 'ca', country -'us', shape = 'triangle' as inputs in respective placeholder elements. The search can be initiated by pressing enter or clicking the input box label, after typing in the input. The filters can be reset by clicking the UFO Sightings at the top left corner of the webpage. The table showed 2 results for this particular search as displayed below:

<img width="1437" alt="Screen Shot 2022-11-14 at 7 03 50 PM" src="https://user-images.githubusercontent.com/111387025/201673453-bcef5016-123d-4f5e-95ff-36b53f7a5d25.png">

## Summary
### Drawbacks of the webpage:
* The user needs to be quite precise about the date, place and shape of UFO sighting, in order to make sure that the webpage shows the desired outcome. For example: if a slightly different date is used while searching such as '2/1/2010' instead of '1/1/2010' and if the table does not have the data for that specific date, then the table will not show any result at all.
* The webpage takes in the inputs for search which is case sensitive. For example: If a user uses 'US' as a country to search instead of 'us', the table will not show any results.

### Recommendations:
* The input for search based on date can be updated using a filter, to accept a date range, so that even if a precise date is not known, the user can still see the results by referring to a date range. For example, if the user searches for the data using a date of specific month i.e. '1/2/2010', even if data for that specific date does not exist, but the results can still be shown for that whole month, using the filter.
* In order to assist the users in a better way, the search can be made case-insensitive. In this way, it would not matter if a user uses upper or lower case while typing in the city, state or country, he will still be able to see the results. For example, if the user types in 'US' instead of 'us' in the input for country, using the filters the table should still be able to show the results, rather than no results at all.
