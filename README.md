# Object_Avoidance_Surveillance_ROBO
The project includes concepts of Artificial Intelligence, Internet of Things and Robotics. 
A GPS module is made which sends the current location on a mobile phone application. A surveillance robot is made which is an object avoidance robot powered by Machine Learning and IoT concepts that hepls in avoiding objects. The robot is also installed with a Web Camera which send the live footage to the user and also the GPS location sent by the module installed in it.


COMPONENTS:
•	NodeMCU 
•	RaspberryPi-ZeroW
•	GPS Module –Neo6M
•	Servo Motor
•	L298 Motor Driver
•	DC Motors
•	Ultrasonic Sensor
•	Logitek C310 Web Camera                     

SOFTWARE USED:
•	Arduino IDE
•	Google Firebase Cloud service
•	MIT App Inventor
•	MobaXterm

GPS Tracking Device:

->With the help of MIT App inventor, we get the live location of the GPS module. The Application has been shared as well.

  •	Here we have used GPS Neo6m module for getting the live location of our vehicle.
  •	As soon as the module is activated, it receives the values of the latitude, longitude, time and the date via satellites.
  •	Using the library of Tinygps++, we extract the latitude and longitude and send them directly to the Google Firebase cloud service.
  •	This Firebase stores the data so that it can be extracted by the android application globally.
  •	The coordinates obtained is then passed to the Google Maps which displays the live location of vehicle.
 
 

