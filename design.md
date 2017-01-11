#Design Document

##Diagram
![](doc/diagram.png) 
The app starts with an authentication screen, where it is possible to login with different methods. After the authentication, you will head to the home screen. From this screen, you can navigate to the difference activities implemented in this app. Until now, the activities I had in mind are the step counter, the activity for running, and the activity for looking up exercises.

If wished, the data of the activities, like to total amount of steps or distance ran, can be saved into a database.
Exercises could also be stored in something like a favorite list. There also would be something like generating an workout schedule.

## UI Sketches
![](doc/sketches.png) 

##API's and plugins
I intend to use the workout API from https://wger.de. This is an API containing all kinds of exercises.
This API is needed for the exercise activity, where the user can look up all kinds of exercises.
I will also use Google Maps, to generate or plan a running route for the user. The distance of the route will be calculated.

##Databases
The things I intend to use for saving data are FireBase for online use and SharedPreferences for local data save.



