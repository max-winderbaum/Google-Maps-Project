#Google Maps Project

##Outline
This is a web-app that allows a user to search for, select, and display a route from the user's current location to the selected destination.

##TODO

- ~~Get the user's current location and show it on the map~~
  - ~~Use `navigator.geolocation`~~
  - ~~Center map on retrieved latlng at some default zoom level (13-15 are pretty good defaults)~~
  - ~~Show custom user icon~~
  - ~~Show other information about geolocation result (accuracy, elevation, heading, etc.)~~
  - ~~Update user's location as they move around~~
- ~~Provide a button/panel that allows the user to type in a destination~~
- ~~Perform a search for nearby POIs that match the entered destination input~~
  - ~~Use the current map's center/viewport bounds + zoom as params for the search~~
- ~~Results of the search should appear in a list in some manner for interaction (maps icons, sidebar, pop-up, etc.)~~
  - ~~Show additional info about each search result (distance away, provided images/icons, search result type, etc.)~~
  - ~~Cool list container / UI layout~~
- ~~Each entry should be selectable~~
- ~~Show/highlight an entry on the map if it is selected~~
  - ~~center/zoom the map based on user's and destination location~~
  - ~~make cool animation when transitioning~~
- ~~Retrieve/plot a route from the user's current location to the destination~~
  - ~~Show additional info about destination via pop-up balloon over destination marker~~
  - ~~Use custom icon for destination marker~~
- ~~Accomodate viewport sizes ranging between phone and desktop~~

##Getting Started
First make sure you have node.js installed... without that nothing works!  You can either install it with your favorite package manager or with [the installer](http://nodejs.org/download) found on [nodejs.org](http://nodejs.org).

Once you have node set up, you'll need to install app-specific packages to facilitate all of the automated building for the Challenge.

Here are the steps:

1. cd into the project's root directory (i.e. `Google-Maps-Project/`)
2. This project relies on grunt-cli, and bower to do all the heavy lifting for you, so: `npm install -g grunt-cli bower`
3. Now, install all of the base project dependencies: `npm install && bower install`

##Running a Development Server

Simply run ```grunt serve``` and you will start a local development server and open Chrome.  Watch tasks will be running, and your browser will be automatically refreshed whenever a file in the repo changes.

If you would like to have your server be accessible to other devices on your local machine use the option ```--hostname=0.0.0.0```

If you don't like your browser being opened for use a ```--no-open``` flag to disable the feature
