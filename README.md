# Neighborhood Map Project

This is my fifth project of fullstack web development. This includes a neighbourhood map for selected places. 
Here I included the famous places of Abu Dhabi. 
 
The app allows you to filter the list down, and in return displays the locations on the map along with 
some additional info pulled from Foursquare where available (such as websites and phone numbers,
although none of the places listed require a reservation.)

# To run:
Open project.html to run the web application.
I used knockout file and css file for styling.

#### The "initialLocations" is a list of all the places' basic location info (name, lattitude longitude).

# The model:
I use "Location" object.
1. It will get all basic info(include address website) from Foursquare's API
2. It will change all the info into a unified format.
3. Using ko.computed to determine whether to show the place on the map.
4. Add "click" event on the "marker" to show basic info.

## View of project:
1. It will create the map on screen
2. Will make the "Location" Object and put them into a "ko.observableArray"
3. "this.filteredList" is "ko.computed" function which will determine whether to show the place on the map.

