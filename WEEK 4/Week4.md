# Week 4

## Fusion 360 for large Laser Cutter

This week commenced with the continuation of adding fastners on Fusion 360 to the CNC operated large laser cutter. It has alot of components and required detailing for aligning the components to each other. The machine was partially disassembled and reassembled to measure the dimensions of fastners.

[3D Model of large Laser cutter](IMG16.png)

## PCB Testing

The next task was to test the functioning of the PCB for the large laser cutter which was soldered the previous week. We removed all the wirings to the pcb that was placed originally and replaced it with the newly soldered one. The machine turned on but there was a short circuit while trying to run the machine, so we removed the pcb and decided to check the connections with the multimeter.

Upon checking, there were 2 resistors that were not soldered properly and the connection to the supply voltage from the pcb to the machine was wrong. 

The microcontroller on the PCB was also flashed using VS code.

[Connections  of the machine with the new PCB ](IMG17.jpeg)

## Inspection of Large Laser Cutter

After making all the modifications, once again the machine was tested, but the laser was not cutting the plywood. We opened up the connections and found that it was not caliberated properly. 
After caliberation, it worked successfully. 

## Motor Driver Modelling

I was provided with a motor driver and a cable connnectorto measure and model it on Fusion. With the help of the vernier callipers, I measured its overall dimensions and started with the sketching the model. I tried to navigate myself through all the essential features that Fusion 360 offered to effiently sketch the motor and the cable connector.

[Motor Driver ](IMG18.png)

[The connector](IMG19.png)

## Stepper Motor Testing

For the next task, we were supposed to test the 2 PCBs that we had soldered previously for a CNC milling machine. For this, we connected the stepper motor to the motor driver, the motor driver to the PCB and gave 24V power supply and controlled the movements of the motor through UGS software, which is an open source software for CNC machines. As a result, we were able to control the motion X,Y & Z directions as desired.

[Motor Testing ](IMG20.jpeg)

## Wood Cutting

We then proceeded to cut wood to small pieces using a machine. For very large pieces, we had to break it to smaller ones to fit it into the machine, for which we used an electric cutter. To be able to use these instruments, we were first provided with a safety training, following which we commenced the task.

[Wood cutting machine](IMG21.jpeg)

[4 boxes of cut wood](IMG22.jpeg)
