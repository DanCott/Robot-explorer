# Robot-explorer
a simulation of a Mars rover built on an Arduino platform
My plan is to setup two way comunnication between a PC host and the Arduino built into the rover.
The com would be over two LoRa modules.

The premis, the rover using a time of flight laser distance finder would do a 180 scan from it's current position, it will also have a 
compass so that a direction and a range can be plotted on the PC.  The plot points would be graphically shown so that the user can 
determine where the user wants the rover to explore.  The user would list the directions/way points he wants the rover to go to, then he
would down load the file and after a few seconds the rover would head off on the coarse plotted.
The rover would send data back to the PC showing distance and heading as it travelled.  Though the obsticals plotted are only items in the
room the challange is to make the list send the rover on more and more difficult routes and still get to the objective(s) and back 
without colliding with anything.  The rover could be up graded with arms and claws or scoops to add to the challange.  
The user will be able to modify the firmware to improve responce, accuracy and functions.

That is my scope for this project.  The software would be lic under the MIT lic.
