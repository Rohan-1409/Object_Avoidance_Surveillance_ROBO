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
 
 
 Surveillance Robot:

•	For making the robot avoid obstacles in path so that it can be self-driven, we make use of Artificial Intelligence.

•	In this process, we initially train the robot by our self by manually operating it in a particular area with some obstacles.

•	We ourselves turn the robot in a desired direction when the robot approaches any obstacle.

•	In this way we get a large number of learning data which shows the instantaneous speeds of both the left wheel and right wheel with the respective distances between SONAR and the obstacle. A piece of learning data is also shared as an excel sheet.


->Linear Regression Machine Learning Algorithm

Linear Regression algorithm shows the relationship between 2 variables and how the change in one variable impacts the other. The algorithm shows the impact on the dependent variable on changing the independent variable. The independent variables are referred as explanatory variables, as they explain the factors the impact the dependent variable. Dependent variable is often referred to as the factor of interest or predictor.
 
->TRAINING

While training of the robot we built a maze so that our robot could get all the possible type of data in a way that it could learn every type of scenario.

 
->CALCULATING THE WEIGHTS:
 
Here after getting the learning data , we use it for calculating the weights by linear separatrix method.

 

