# Northgate Bar Locations,
Specials and Routes

Team Leader: Kayla Davis, kayladawndavis@gmail.com
Other members: Jimmy Barnett, trejimmy5562@tamu.edu
               Zach Johnson, zachjohnson@tamu.edu

What do you want your web map and/or app to do?
  INTERACTIVE ELEMENTS
    We will include popups on each bar detailing:
        Bar names
        Age requirements
        Specials
        Attractions
        Address & Coordinates
  ROUTE TRACKER
    We plan to add a route function that calculates a route to go to as
    many bars as possible in as short of a time as possible.
        Route for 18-20 year olds
        Route for 21 year olds
    Similar to google maps routing but fixed route for best NG bar
    hopping route.
  BASE MAP
     We plan on doing one similar to Aggiemap
        2D is all that's necessary
        Building outlines
        Adding bathrooms and roads
        
What does a "successful" web map and/or app do?
  Ease of use – user-friendly interface with clear icons and functions
  Working interactive elements which provide useful information
  Working routes which provide a clear route through NG
  Separate tabs for different users, I.e. one tab for 18-20, one for 21+.

What is your minimum viable product?
  2D map with routes and interactive elements for each bar. No user
  issues and working elements.

What other web maps and/or apps do the same thing as yours?
  Google maps: has many of the same features: a 2D basemap, walking
  routes, and interactive elements for buildings

  Aggiemap: very close to our proposed final product. 2D basemap with
  building information, routes, bathroom locations, popups. 

How is yours different or better?
  Ours will be better because I propose we have less
  features/interactive elements. In my opinion these occasionally
  overload the user, so perhaps separating the user elements into
  easy-to-identify folders and adding less interactive elements so that
  routes/bathrooms/bars are easily found and distinguished, as
  opposed to aggiemap which has extensive layers and options which
  can be overwhelming and not user-friendly.
  
 Design: Will be similar to aggiemap
      2D buildings instead of shadowed/simulated 3D
      Routes highlighted
      Hamburger menu:
          1. toggle routes
          2. switch between age groups
          3. locate bathrooms
      Interactive bar popups when clicked
      
  Software Engineering:
      Leaflet would be a useful library to use.
      The interactive elements and routes would be added using JS, like the onclick hamburger menu, routes, and popups
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
