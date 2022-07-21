# UFOs Challenge

### Challenge Overview
Dana’s webpage and dynamic table are working as intended, but she would like to provide an in-depth analysis of UFO sightings by allowing users to filter for multiple criteria simultaneously. Note that table filters for the city, state, country, and shape were added.

### Resources
- Software: Python 3.7.6, VS Code
- Data Source: data.js

**Changes in HTML**
- Removed the list group containing original button.
- Added list of 4 groups in the container to add the current filters.
- 
**Changes in app.js**
- Added a filters variable to hold all of the filters as an object
- Created 3 variables for element, value, and filterId 
- Added an if statement to add the filterID and value to the filters list, else clear the filter from the object
- Created a function to filter the table once data is entered (this is where the forEach is used to keep data that matches the filter values)
- Oberve that an event is added (D3) to listen for the changes to the filtered data.

### Summary
Editing filter helps with searching specific UFO sightings. The data will populate in the table if the filters match. Oberve that when removing the filter button, there is not a clear way to determine how to cleear the filters.

### The Webpage
Check the webpage to see the filters.

**Recommendations**
- The filter search should be remolded for easy use.
- Remodel the webpage by rearranging the visuals.


