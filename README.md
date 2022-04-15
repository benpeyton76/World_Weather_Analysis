# ***World Weather Analysis***

## ***Overview***
The purpose of this project is to build an app that can collect, analyze, and visualize weather data from across the globe. The PlanMyTrip app carries out all of these tasks and is a helpful tool in the travel industry. By using PlanMyTrip, clients can make plans to vacation and chose their destination based on local weather forcasting. 

## ***Retrieve Weather Data***
First, we will generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, retrieve the current weather description for each city, and perform an API call with the OpenWeatherMap. Then, we weill create a new DataFrame containing the updated weather data.
We will retrieve the following information from the API call:
- Latitude and longitude
- Maximum temperature
- Percent humidity
- Percent cloudiness
- Wind speed
- Weather description

![Capture1](https://user-images.githubusercontent.com/87077325/163581205-6fd24355-9196-4613-8c86-9d5bdddd42bc.PNG)

## ***Create a Customer Travel Destinations Map***
In this section, an interactive marker layer map is created. The customer will input weather criteria to match their desired preferences. The preference input will identify and generate travel destinations with pop-up markers that include:
- Hotel name
- City
- Country
- Current weather description with the maximum temperature.

![image](https://user-images.githubusercontent.com/87077325/163597674-998a5b6d-4b60-4dcb-8f84-8a598dcc7a7c.png)


## ***Create a Travel Itinerary Map***
Using the Google Directions API, a travel itinerary is created that shows possible routes between four different cities by request of the customer. The itinerary will also contain pop-up markers with the information that was previously created in the destination maps.

![image](https://user-images.githubusercontent.com/87077325/163598681-5bb0c852-d2e8-48c8-a8c2-93cea0b2e3e8.png)


![image](https://user-images.githubusercontent.com/87077325/163598611-8bf998b4-580e-465f-ad1f-5d1cbc8c2baa.png)

## ***Summary***
With these tools in hand, making vacation destination choices will be a breeze. It gives the customer the freedom to choose which destinations best suit the needs of the kind of vacation they want to take. This is also a convenient and efficient way to for the travel agency to book vacations and help customers find their dream destination.
