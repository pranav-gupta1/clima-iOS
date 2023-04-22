#Clima

I created an iOS application called Clima. It is a weather app with a few extra features, including changing its background/aesthetic based on the system setting (light or dark mode). There is a button in the top-left to get the user's current location and show the weather for that city using a prompt with the option of precise or general location. The rest of the top bar has a search area where the user can type in a city to see weather information about. The temperature, symbol (ex. sun, clouds, haze, wind, etc.), and city name and weather type update when a new city is entered. It was programmed using Swift in Xcode. The main frameworks implemented were Networking in Swift, JSON Parsing, APIs, and Core Location. I used Apple's SF Symbols for corresponding icons. The main part of the program was using the Open Weather Map API and getting an API key from it to get the weather from around the world. This API was implemented smoothly in the code to get accurate data. Also, a JSON-Viewer extension was used to parse the JSON files. Exception handing is also present.



//Note: I learned the main concepts from an online course. Created individually and checked as I went, in addition to Swift and Open Weather API documentation. Credits to Angela/London App Bewery for reference.
