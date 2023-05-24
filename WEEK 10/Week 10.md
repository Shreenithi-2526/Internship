# WEEK 10

## Calibration of Load Cell

The task was to calibrate a s-type load cell which has a capacity of 300kgs with a HX711 development board. Firstly, we had to solder the wires from the load cell to a female-female connector wires to fix it to the board and checked if the load cell worked. Next, we took an object of known weight and weighed it using the load cell. There was some error and therefore it needed to be calibrated. 

To calibrate this specific device we did some research about its components and functions to understand how to calibrate it. Following the research, we found that the four buttons on the board are used for calibration. 

After sucessfully calibrating the device, we had to solder the connecting wires from the load cell to male-female connector to establish stable connection. After doing this, we again weighed the known object but this time the units changed from kilogram to grams, we then played around with the device and successfully brought the unit back to kilograms.

Lastly, we documented the calibration process on GitLab.

[Load cell](IMG50.jpeg)
[HX711 Board](IMG51.jpeg)


## Comparison between controllers

Following up from the previous week, we drew a comparison table between 12 different potential micocontrollers to short list the ones we could use for the project. Some important parameters that we are looking into for the selection of the controllers are clock speed, memory, if it has FPU or not, cost, if the microcontroller is easy to solder or not, the number and avaliablity of peripherals, number of I/Os, programming language used etc.

In order to get all this information, we looking through the official websites of the microcontrollers and their data sheets.

We also researched about various communication protocols like SPI, I2C etc. to understand how they work and what would be the best to use.

## Ball Screw Dissassembly

We had to disassemble a ball screw arrangement which is a part of the antenna system being made, as the ball screw shaft was faulty. In this process, the steel balls fell out of the ball nut and we had to carefully insert them back again.


## Moving Machines

For a new fibre laser cutter that is getting delivered, we needed to organies the machinery area to make space for the machine. To do so, we first planned on the outlook of where to place the existing machines and then unscrewed the drill press from the ground to move it. Next, the 12 tonn hydraulic press machine was also moved away. To move the upper half of the lathe machine, we used a small crane to lift it. 

[Lathe machine on crane](IMG52.jpeg)


## HSRW Learnings

We got to dig deep into microcontrollers this week. The foundation provided in the course Microcontrollers at the university was indeed applied to understand about the various peripherals, communication protocols and about microcontrollers itself. Further, since I already had some experiences about research on suitable controllers for our group project and the project in the course Practical Electronics, it aided to understand the parameters while selecting controllers.