## Building a Soft Finger with 3 DOF
![test](imgs/finger/finger.gif)

### Abstract
---
This project seeks to make a single robotic finger that can be controlled in any direction. This finger will utilize a 3 chamber design as demonstrated in the cited papers. It’s goal is to be able to extend as well as bend/curl along any direction. My original plan was to build two different models using pneumatic artificial muscles in addition to a custom silicon molded actuator. Unfortunately, the nylon sheathing I got was too small for the balloons to inflate. 

This actuator will fall into the fiber-reinforced-actuator group, as the entire structure will be wrapped in an inextricable layer. There will be three controllable chambers and varying the pressure in each of them relative to the others should allow for curling motion in any direction relative to its nominal direction.

The purpose of this project is to determine the abilities of actuators and their difficulty of manufacturing. The future goal is that multiple of these actuators could be combined to form a versatile gripper for robotic applications. 


### Design
---
I opted to design the entire actuator out of a single piece of silicon. This meant that this was insanely tricky to mold as there were many internal angles and I do not have access to a 3D printer with dissolvable filament. I designed a 4 step mold process in which the core of the actuator is molded and then the edges are molded around that.

 I used Onshape for the first time and things went fairly smoothly:
INSERT CAD PIC

Notable design considerations:
- 3d print molds instead of using cardboard
- Mold in multiple steps as opposed to a single step
- Increased wall thickness and dimensions from reference papers



### Fabrication
---
This yielded a total of 5 3d-printed parts. 
INSERT ALL PARTS HERE


Three of them are glued together to form the mold for the central column
INSERT MOLD PIC HERE

The other parts are used together to hold the core and mold silicon into an arc around it:
INSERT ARC PIC

Here are some more pictures from the molding processL
See pictures below

### Results
---
Here you can see the final actuator:
INSERT FINAL PIC OF ACTUATOR

This actuator works in the ways I anticipated! By controlling the pressure in each chamber, and the ratio of the pressures between chambers the actuator can rotate in a circle and curl in any direction.
INSERT GIF HERE


### Evaluation
---
Calculations for 90* bend of actuator
Orange chamber 7.5lbs
Blue chamber 5.5lbs
Green 6.5lbs to 90*rotation
G &B 10lbs less angle

Area of plunger:
.75” radius^2* pi = 1.767” inches square 

PSI Calculation:
Hence:
Orange: 4.2psi
Blue: 3.11psi
Green: 3.67psi
Green & Blue at the same time: 3psi for each chamber (less rotation than the single chambers)

When converted to kPA, these values are all less than 35 kPa. This is less than the actuation pressure for the previous wrapped actuator and fabric-pneumatic actuator. 

The actuator is easier to actuate along one of the 3 cardinal directions. This actuator has roughly a 2” reach in every direction. When all chambers are inflated it simply extends roughly 25% of it’s length. 


### Lessons Learned
---
Molding is hard!
Circular molds are especially difficult
3d printing isn’t always the answer, A cardboard mold could have been made as well
Single use molds are an option-- THis could have saved me a lot of time since it was hard to print parts


#### Works Cited
 https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=131850&tag=1
 
 https://www.mdpi.com/2076-0825/8/2/32.

