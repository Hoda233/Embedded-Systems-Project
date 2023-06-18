<br/>

## Table Of Contents

- [About The Project](#about-the-project)
- [features](#features)
- [Demo](#demo)
- [Schematic Design](#schematic-design)
- [Speed Control APP](#speed-control-app)
- [Contributing](#contributing)
- [License](#license)

## About The Project

This project is a line follower and maze solver robot that uses a PID algorithm to navigate through a black line on a white surface. The robot is also equipped with sensors to navigate through a printed maze on a white surface. In addition, the robot is provided with a mobile application that scans the top view of the line print and adjusts the robot's speed accordingly.

Our team, <em><b>Ninja</b></em>, developed this project as part of our Embedded Systems course at Faculty of Engineering, Cairo Univerity. We used an Arduino Uno board to control the robot's motors and sensors and programmed it using the Arduino IDE. The mobile application was developed using Python.


## Features
* Line following: The robot uses a PID algorithm to follow a black line on a white surface.
* Mobile application: The robot is provided with a mobile application that scans the top view of the line print and adjusts the robot's speed accordingly.
* Maze solving: The robot can navigate through a printed maze on a white surface using its sensors and PID algorithm.


## Schematic Design

![Capture_1](https://github.com/asmaaadel0/Embedded-Systems/assets/72188665/2f360ebb-bc28-4bf0-bc78-fafabb2a6169)

![Capture_2](https://github.com/asmaaadel0/Embedded-Systems/assets/72188665/28abc2cb-436d-40e3-a2f1-be9c89de0733)


## Speed Control APP 🚗
<p>the aim of this application is to control the speed of the car
here we connect our application with Bluttooh if we detect the car and the car is on the staright line our Application sends '1'
to the hardware so the hardware increase the speed and if we detect the can on the curve we send '0' so the hardware decrease the speed
we used image processing techniques to control the speed which are </p>

<li>1- using Hough transform to detect lines</li> 
<li>2-apply dilation on hough transform results so the lines becomes wider </li>
<li>3-detect the car (red color) to make it easy for us and to make the aplication faster we assumed that the car is always a red color detection</li>
<li>4-then we check if the car is on the line so increase the speed else decrease </li>
<li>5-we have added some check conditons so it will send '1' or '0' if the state have changed not all the time</li>

here is an example of our application detection 
if the car is on the straight line you will find a white circle inside the object 
![image](https://github.com/asmaaadel0/Embedded-Systems/assets/88630231/0c52c4a3-3ab3-465a-b15e-13fa484d8fc9)


## Demo

Line Follower 



https://github.com/asmaaadel0/Embedded-Systems/assets/72188665/9e655b52-0ede-4d0a-a775-e17482c85610



Maze [ Scanning ]: 



https://github.com/asmaaadel0/Embedded-Systems/assets/72188665/73f66ddb-291e-4079-a758-6c613855b7e8


## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
- If you have suggestions for adding or removing features, feel free to [open an issue](https://github.com/asmaaadel0/Embedded-Systems/issues/new) to discuss it.


 ## License
- The project is open source and released under the MIT License.
