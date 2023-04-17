# Week 5

## PCB testing with inductive probe

After the working of the motors in x,y & z directions, it was time to test if the motors stop working when a a ferrous object is in the vicinity.

For this, we used an inductive sensor and connected it to the pcb. In order to connect the pcb, we had to first solder the terminals of the indictive probe to a connnector with 3 wires. Initially only the x limit was functioning ie, the motor stopped rotating and an alarm state was triggered when the sensor detected a metal object.

For the y & z axis, the sensor was not triggering an alarm state and upon analysis, we found that improper soldering could be posing an issue. In particular, for the z-axis the transistor that was soldered had some issue as its padding was ripped off. Upon connecting it with a wire and testing again, the pcb for CNC milling was successfully ready.


## Testing Plate

The next agenda was to design and laser cut a plate to fix a stepper motor to an aluminum rod for conducting a test. We tried visualizing and understanding the positioning of the motor and all the surround's constraints to create an efficient model. For this, we initally created a design but it was not very stable, so after receiving some inputs, we modified its dimensions for stability.  

After the model was ready, we proceeded with the process of laser cutting. The final sketch on Fusion 360 was saved as a dxf file and then exported to visicut software, where all the appropriate settings such as material, speed, power was set. This file was imported to UGS software and was ready for cutting. 

The final model proved to be unstable as there was a high possibility that it would break from the power of the motor. We made some minor changes in the sketch by increasing the overall breadth and reducing distance between holes.

[Old piece](IMG23.jpeg)

[Revised plate](IMG24.jpeg)

Following this, we repeated the process of laser cutting and this time it was successful.

## Two more Testing Plates

2 more motors of different sizes were to be tested. For this, we used the existing design and modified its size to match with the dimensions of the new motors. Following this, we proceeded with the same process of laser cutting the 2 plates using the laser duo machine. 

[New plates](IMG28.jpeg)


## Testing of Stepper Motor

The testing plate was assembled with the motor and a pulley along with an aluminum profile and a belt.The belt was secured tightly with cable ties to provide maximum tension. For the testing, the motor was connected to a driver and pcb similar to the connections that was made for the pcb testing of the cnc milling machine and a liner guide mechanism is used to move along a staright line. The goal was to make the motor move precisely, for this we changed the steps/mm which was found through a calculator online in the UGS software and consequently changed the microstepping of the motor driver. After conducting repeated tests, it was concluded that precision was achieved with different driver microstepping values.

[Setting up](IMG25.jpeg)

[Conducting the test](IMG26.jpeg)

This test was carried out for 2 more stepper motors of different sizes using pulleys of appropriate diameters and teeth & another motor driver. For every motor the experiment was conducted with various driver microstepping and accordingly the calculations for steps/mm differed. The calculated values was then changed on the UGS software. Upon performing this task for the last two motors, it was observed that the calculated values of steps/mm were not providing accurate results, so changing the values by trial & error we achieved the desired accuracy.

[Settings on UGS](IMG29.png)


The purpose of this experiment was to observe if the motor could move precisely to upto 0.01mm to any desired distance. These motors would later be sold to a University for a cylindrical positioning system.

Then we did a brief testing of a gear system to check if 0.5 degreees of accuruacy could be reached. Some calculations were made using the teeth ratio to motor & gear.

[Spur Gear system](IMG30.jpeg)

## Tapping Machine

We were trained by our colleague to use an electric tapping machine. The aim was to tap all the holes in an aluminum profile. We fixed an M5 tapping bit and placed the profile on the vice. Oil was sprayed on each hole and we tapped all the through clockwise & anticlockwise. This was done for 2 similar profiles.

[Tapping Machine](IMG27.jpeg)

## Cutting oF Aluminum using Bandsaw

We then moved on to cutting some large aluminum profiles using the bandsaw, to reduce its size for easy mobility and storage. Pieces that could not be used anymore were discarded.




