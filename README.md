# Bipedal-Robot
Srishti 2020

![](https://github.com/Aayush-765/Bipedal-Robot/blob/master/Images%20and%20Videos/Images/Front%20View.png)

# Abstract
The Bipedal Robot is a humanoid robot modeled to mimic the walking of a human, the Robot is designed to have 6 degrees of freedom in total, implying 3 degrees of freedom in each leg, 2 of which are used for moving the leg in forward or backward direction using Servo motors at each joint(hip and knee), while the other degree of freedom is used for balancing the robot using another servo motor when standing on one leg, the mechanical model is designed to avoid extra weight so that the balance of the robot is more stable. The robot is actuated by using the microcontroller Arduino.

![]( https://github.com/Aayush-765/Bipedal-Robot/blob/master/Images%20and%20Videos/Images/Work-Flow.png)

## Motivation
Bipedal robots are able to move in areas that are normally inaccessible to wheeled robots, such as stairs and areas littered with obstacles that make wheeled locomotion impossible, also they can be an asset which can work in hazardous conditions.

## Mechanical Aspect

1. Robot’s size selection

	Robot size plays a major role. Based on the cost of project, materials required for fabrication and the no. of actuators can be determined. In this project the size of the robot is preferred so a height of 300mm is decided which includes mountings of the control circuits, but the actual size of the robot is 230mm without controlling circuits.

2. Degrees of Freedom (D.O.F)

	Human leg has got 6 degrees of freedom (Hip – 3 D.O.F , Knee – 1 D.O.F , Ankle – 2 D.O.F) , but implementing all the 6 D.O.F is difficult due to increase in cost of project and controlling of the actuators which become complex, so in this project reduced degrees of freedom is aimed so 3 D.O.F(Ankle , Knee and Hip) per leg has been finalized.

3. Foot Pad Design

	The stability of the robot is determined by the foot pad. Generally, there is concept that oversized and heavy foot pad will have more stability due to more contact area. But there is a disadvantage in using the oversized and heavy foot pad, because the torque requirement of the motor is more and lifting the leg against the gravity becomes difficult. By considering this disadvantage an optimal sized foot pad was used. Dimensions of the foot pad are 75*70mm.


## Electronic Aspect
1. Power Source 

	11.1 Volts 2200mAh Li-Po battery is used as the power source for powering the Arduino as well as the Servo motors in the robot.

2. Actuation

 	All the movement is actuated using Metal gear Servo motors, one motor is used for a single degree of freedom, so six Servo motors in all are needed for the 6 degree of freedoms in the robot.  

3. Motor Selection

	The choice of motors was based on the idea of reducing weight as well as creating a less complex feedback mechanism, hence the choice of using high torque metal gear position control DC Servo motors was appropriate under the given constraints.

4. Microcontroller 

	Arduino UNO R3 is used as the microcontroller which can operate six Servo motors at a time, enabling various types of motion such as forward, backward etc. 

## Cost Structure 

| Materials  | Cost(INR) |
| ------------- | ------------- |
| 6 DC Servo Motors | 3000 |
| Arduino UNO R3  |400 |
|  11.1 Li-Po Battery  | 1800 |
| Miscellaneous | 300 |
| Total | 5500 |

## Applications
1. The movement of the robot can be controlled by using a remote controller.
2. The bipedal robot can assist humans to carry out the tasks or activities in hazardous environment which could eliminate human's risk of injury or life casualty.
3. They can be used for household work for the disabled or someone  suffering from any disease.
4. They are used at rough terrains where wheeled robots cannot be used.

## Limitations
1. Currently the robot has only 6 degree of freedom, so the motion has some constraints.
2. The bot is battery operated with small power supply, so regular change of battery is required.
3. Computer Vision or Ultrasonic sensing is not enabled, which means object detection cannot happen. 

## Future Improvements
1. Size can be changed so as to human activities and task. 
2. Degree of freedom can be increased to give proper flexibility in all directions and orientation.
3. Using Computer Vision for Obstacle detection, human recognition and corresponding Path planning.
4. Using IoT, this bot can be controlled from anywhere and can be live-streamed using webcam. It can be made autonomous using ML

## Team Member
1. [Aayush Ranjan]( https://github.com/Aayush-765 )
2. [Chirag Baghla]( https://github.com/chiragbaghla )
3. [Ila Dwiwedi]( https://github.com/ildwi)
4. [Meenakshi Gausingha]( https://github.com/Meenakshi1791)
5. [Prawal Pratap Singh]( https://github.com/ppsr7355 )
6. [Roshan Kumar Choudhary]( https://github.com/roshan-121)
7. [Upasana]( https://github.com/Upasana202)

## Mentor
1. Dhruv Sehgal
2. Kunal Kumar

## References
1. https://core.ac.uk/download/pdf/29403117.pdf
2. https://www.researchgate.net/publication/326668524_Implementation_of_6-DOF_Biped_Footstep_Planning_Under_Different_Terrain_Conditions
3. https://www.youtube.com/channel/UCtwaWPOXEBysZLh1rrPzwF
4. https://youtu.be/2kSWHbWnVyo
5. https://www.solidworks.com/
6. https://www.arduino.cc/
