rocketlaunchapp
=================

rocketlaunchapp app is meant to help identify launch windows for RocketCo who will be providing flights to Mars. 
The launch window requires certain weather conditions to be successful. It uses OpenWeatherMap API to determine the optimal launch windows within the next 5 days.

Running Steps
----------------

1. Clone the repo rocketlaunchapp to your local directory.
2. Import the project in anypoint studio as a mule project from exiting folder and run as mule application.
2. Do a GET call using postman with the url http://localhost:9000/launchwindow?id=<cityid> to access the launch window by City Id (eg: Type id=7839805 in the url for viewing Melbourne's launch window)
3. Do a GET call using postman with the url http://localhost:9000/launchwindow and it will display launch window details for the following cities:
    CityId,CityName
    7839805,Melbourne
    2073124,Darwin
    2163355,Hobart
    2063523,Perth

