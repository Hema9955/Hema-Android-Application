# Hema-Android-Application

<----------------------- DEVELOPER NOTE---------------------------------->

ABOUT APP: This app will provide the venue locations and full details about the location.
User can view photos taken, set specific location as favourite.

 Design Pattern : MVC ( Model, View, Controller)
 Network Interactions: Volley + Gson libraries
 Image Loading and caching : Picasso library
 UI: RecyclerView

 Challenges:

 1. IMAGE LOADING: Loading images from the given url is the difficult part. If we can't handle bitmap in a proper way
 application will crash due to low memory. So to overcome this issue used Picasso library for image loading and caching.

 2. NETWORK PROTOCOLS: While sending request to the server we have to take care of background threads while performing long
   running tasks like fetching data and loading images.
   To overcome this issue, Used volley library for network protocols so that it will manage everything for us.
   It will maintain request queue and it automatically process it so for the better performance used Volley and Gson library's
   to parse the given JSON response with very minimal code.

 <-------------------------------------------------------------------------------------------------------------------------->


