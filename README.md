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
      The interactive elements and routes were added using JS, like the onclick hamburger menu, routes, and popups
      The basemap would be used in html, and the content of the interactive menus and popups
      The style of each popup, route, and menu would be done in CSS
      
  Data:
      Building locations & shape
      Specials at bars
      Bar age requirement
      
  Computing:
      A mixture of html, Javascript and CSS would probably be the main requirements of making this web map.
      Not much data processing would be needed as the map and routes would be static and the information unchanging.
      
  Project Managment:
      Data collection will be done by all members split into areas. Create a cohesive map of each building 
      and important features (bathrooms)

      Coding will be done in parts, with interactive elements and routes
      being split by age and each done by a separate member of the group.

      Finally will be consolidated and tested
  
  Testing:
      All group members will test map on separate computers
      Contract friends to try to use on their own devices + give feedback
      Evaluate and fix any errors/confusing elements
      At least 20 people to test it
      Use every feature in test, attempt to navigate map without assistance
      If users find features easily, understand what they are looking at, can navigate without assistance and errors it is a success.
  
  Potential Issues:
      GPS accuracy of buildings
      GPS battery
      Coding errors
      Problems integrating different functions into same map

All code here was written by Jimmy Barnett for a project with group members
