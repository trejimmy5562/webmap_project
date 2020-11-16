# Northgate Bar Locations
Specials and Routes

### INTERACTIVE ELEMENTS
    Map includes popups on each bar detailing:
        • Bar names
        • Age requirements
        • Specials
        • Attractions
        • Address/Coordinates

### BASE MAP
      Basemap is a clean, minimal streets map to easily navigate directions and distances
        • 2D is all that's necessary
        • Building outlines
        • Adding bathrooms and roads would be useful
        
### ROUTE TRACKER
    Plan to add a responsive route function that calculates a route to go to as
    many bars as possible in as short of a time as possible, or with variable input parameters.
        • Route for 18-20 year olds
        • Route for 21 year olds
    Similar to google maps routing but fixed(?) route for best NG bar
    hopping route.

  
### Design: 

    Interactive web map similar to google maps layout
      2D buildings instead of shadowed/simulated 3D
      Routes highlighted
      Hamburger menu:
      • toggle routes
      • switch between age groups
      • locate bathrooms
      Interactive bar popups when clicked
      
### Software Engineering:
    Leaflet.js library was used.
      The interactive elements and routes were added using JS, like the onclick hamburger menu, 
      routes, and popups
      The basemap would be used in html, and the content of the interactive menus and popups
      The style of each popup, route, and menu would be done in CSS
      
### Data:
      Building locations & shape/outline
      Specials at bars
      Bar age requirement
      
### Computing:
    A mixture of html, Javascript and CSS are the main language requirements of making this web map.
      Not much data processing would be needed as the map and routes would be static and the information unchanging.
  
### Testing:
      All group members tested map on separate computers
      Contracted friends to use on their own devices + give feedback
      Evaluate and fixed any errors/confusing elements evaluated
      Got at least 20 people to test it
      Use every feature in test, attempt to navigate map without assistance
      If users find features easily, understand what they are looking at, can navigate without assistance and errors it is a success
  
### Potential Issues:
      GPS accuracy of buildings
      GPS battery
      Coding errors
      Problems integrating different functions into same map

All code here was written by Jimmy Barnett for a project with group members
