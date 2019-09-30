# How to Create and use a Google API.
In this tutorial you will learn how to create and use a Google API. Enjoy it!

# Why exactly is an API?.
An application program interface (API) is a set of routines, protocols, and tools for building software applications. Basically, an API specifies how software components should interact. Additionally, APIs are used when programming graphical user interface (GUI) components. A good API makes it easier to develop a program by providing all the building blocks. A programmer then puts the blocks together.

# API Google.
Google APIs is a set of APIs developed by Google, which allow the communication and integration of Google Services with other services. Examples include the Search, Gmail, Translator or Maps APIs.

# How to create an API Google.

1. In order to create a Google API, it is necessary to have a Google account and a bank card that accepts payments online.
2. When you already have a google account, you must go to the url: https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=2ahUKEwiKkLz2v_fkAhUHXK0KHUCVAe4QFjApsur3Qhttp&dql3d3d3d3 % 2F% 2Fconsole.cloud.google.com% 2F% 3Fhl% 3Des & usg = AOvVaw32wCy6el4RVbIZO1m5wyNI
3. The url redirects to the Google console. Once in the Console, we must create a new project and accept the terms of use.
4. Next, we open the menu on the left and select APIS and services, followed by this, click on the box where it says "Enable APIs and services".
5. We select the API we want to use. In our case, the Google Maps places API. If we want to add more APIs, we will have to follow the same steps shown in this section once the process in question is finished and having selected the project we just created.
6. After selecting the desired API, we click on "enable", we will be redirected to the API page, where we subsequently click on the credentials tab and also on the text where it says "To see all the credentials or create others, go to Credentials in APIs and services".
7. We click on the blue menu "Create credentials" and "API key". A window with the API key will be displayed, then desired use is given.

# How to use an API google

You can use the google API for any need you have.
The following place requests are available:
  a) Place Search returns a list of places based on a user's location or search string.
  b) Place Details returns more detailed information about a specific place, including user reviews.
  c) Place Photos provides access to the millions of place-related photos stored in Google's Place database.
  d) Place Autocomplete automatically fills in the name and/or address of a place as users type.
  e) Query Autocomplete provides a query prediction service for text-based geographic searches, returning suggested queries as       users type.

# Example of use.

According to instruction: Use the Nearby Seach Method to find all the restaurant near to the UPY (20.988459, -89.736768) around 2km. In order to fulfill this item you need to add the parameters in the API url.

url = 'https://maps.googleapis.com/maps/api/place/nearbysearch/json?location=LAT,LON&radius=RADIUS&types=TYPES&key=API'
Where:
  LAT: The lattitude
  LON: The longitude
  RADIUS: The radius in meters
  API: Your API google
  
You can use this link to request the information in your data processing system.

# Thanks for read.
# Reference:
https://www.webopedia.com/TERM/A/API.html
