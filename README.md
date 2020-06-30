# Senior-Project-2019-Spring
Abstract:
The main goal of this project is to create four robotic systems that can carry a flag in hurdle
area. There are certain criterias supposed to follow are falling flag, collision with obstacle and each
robot should find other robots. We are planning to achieve one centred system. This main system
consists of one microcontroller, one camera and four robotics devices Each robot will find right
direction for carrying the flag to the target robot. Additionally, the basic working principle of this
system is to detect robots and obstacles at a certain height with a camera located out of the platform
and to establish routes from color selection. With the routes calculated, we will establish a map for
carrying the flag to another robot. The technical process of the Project is mainly based on the
Image Processing, Embedded Systems, Robotics, artificial Intelligence and Control Systems.


Technical Specifications:
In our Flag changing system, we could not use our electro magnet in a direct way because
our device electro magnet uses 6V Our Orange Pi Zero can produce 3.3V in its on-off and we
made one circuit from Orange Pi Zero Voltage source and used orange pi port for on-off. In Figure
1, you can see our BJT circuit shape and may think RC as our electromagnet. When we give 3.3v
from Vc our magnet going to have current and it works. Normally for our Electromagnets
datasheet, we should use 6V but in our project we are going to use Orange Pi 5V pin from collector
because when we use extra power supply, it is going be hard to adjust and we tried to use 5V and
it was successful.Currently we were working on Raspberry Pi Zero with camera module. We can detect
angle and color of our obstaclesFurthermore, we can make a route in an obstacle area for our robots.

You can watch my senior project video:


FOR MORE INFORMATİON, please READ WORD Documantation(https://github.com/btknzn/RelayRacingCode/blob/master/BitirmeProjesiRapor1.doc) AND Look our POSTER (https://github.com/btknzn/RelayRacingCode/blob/master/final%20sunumu%20poster.pptx).
