“Google Maps Organizer” Application -Project Planning

Problem Statement

Primary User

  Google Maps users who want to make multiple categories of lists and want to sort places by proximity, “open now”, and ratings.

User Needs Statement

  As a Google Maps user, I would like to create categorical lists of places with notes/comments, sort them by some key parameters like
  distance and ratings, and share the lists in CSV format and for upload into other user Google Maps accounts.

As-is Process Description

  1.	Search for places in Google Maps and once the user identifies a place to save, the user will “star”, flag as “want to go”, or 
  “label” it and save it to the user google account.
  2.	Create list and “label” a place from Google Maps
  3.	Save the list in google maps without notes or comments.
  4.	Create link to list and share with other Google users.

To-be Process Description

  1.	Launch Google Maps on browser and “Maps Organizer” python application.
  2.	Create export URL from Google Maps and run script to automatically download list into “Maps Organizer”.
  3.	User reviews list and categorizes places as “star”, “flag” or “label”, adds notes and comments, and organizes lists.
  4.	“Maps Organizer” automatically uploads the updated lists into Google Maps account making it available for sharing.

Information Requirements

  Information Inputs
    1.	Google Maps account login.
    2.	A lists.csv file containing a list of location names, open location code (OCD), “star” status, “want to go”, or “label”.
    Information Outputs
    1.	Updated lists.csv file containing updated location names, open location code (OCD), “star” status, “want to go”, or “label”.
    Will also include comments/notes, and reorganized list based on categories.

Technology Requirements

  APIs and Web Service Requirements

   We will need to install the Google Maps API and select the Places API, Distance Matrix API, and Geolocation APIs as part of the
   required package.

  Python Package Requirements

  The application requires the installation of the googlemaps package, pytest for testing purposes, and requests package to handle
  requests to URLs. 

    $ pip install -U googlemaps
    $ pip install –U requests

Hardware Requirements

  The application will be running on my own local machine. We can install the application in a public server and enable it to be 
   downloaded onto desktop devices.
