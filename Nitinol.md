Setup for Soft Actuator Gripper – Nitinol Wire Gripper 

 

For the first Nitinol wire experiment, we need to determine its necessary temperature and voltage required to deform and recover its original under formed shape given a constant length and how much load capacity that it can produce. In the following experiment, we used variety of very small objects for grasping to test the capability of this soft actuator gripper. The materials and apparatus used are listed below: 

 

0.1524m Nitinol wire length with diameter 0.4mm 

Laptop 

Multimeter 

Retort stand with clamp 

Weighing scale 

Weights 

Short lever and long lever 

Phone 

 

Electrical components used: 

12V adaptor 

Jumper wires and USB cable 

Breadboard 

Electrolytic Capacitor 

Arduino Uno (Rev3), type Arduino UNO (Rev3) 

IFR520 MOS module 

Voltage Sensor 25V 

Current Sensor 5A 

Temperature Sensor (Thermistor) 

100Ω Resistor 

LED 

 

Figure 2.1: Electrical wiring for	      Figure 2.2: Schematic view of the setup 

Nitinol wire experiment 

 

The diagram below shows the overall experimental setup: 

 

Figure 2.4: Experimental setup (side view) 

Experiment 1: Evaluating the temperature, voltage and current needed to deform and recover its original shape 

 

Step 1: Prepare the materials and apparatus needed. Set up the experiment based on nitinol wire experiment apparatus set-up layout excluding the weighing scale and weights. Short lever is used in this experiment. 

Step 2: Connect the electrical wiring based on the schematics and diagrams. Connect the Arduino UNO board with the laptop via USB cable and load the programming code.  

Step 3: Make sure the Nitinol wire is in reset position. Open Serial Monitor in Arduino IDE. 

Step 4: Calibrate the thermistor using the multimeter’s temperature sensor and calculate the resistance accordingly.  

Step 5: Measure the ambient temperature using multimeter’s temperature sensor. 

Step 6: Press “+” to increase the voltage increment and “-” to reduce it.  Observe the angle of the lever and the temperature of the Nitinol wire. Make sure that the temperature doesn’t exceed the melting point of the lever. 

Step 7: If the Nitinol wire could no longer recover its original shape further despite the increase in temperature and voltage, record down the temperature, voltage and current needed for the Nitinol wire to recover its original shape.  

Step 8: Press “0” to turn the voltage off and let the Nitinol wire cool down. Observe and record the time taken to deform to its reset position.  

Step 9: Transfer the data from the Serial Monitor to Microsoft Excel and plot charts accordingly. 

Step 10: Repeat step 3 to 9 for 6 times with different ambient temperatures. 

 

 

 

Figure 2.5: Soft Actuator Gripper using Nitinol Wire, at gripper open (Left), half close (Middle), completely close grip (Right).  

                                    

Figure 2.6: Arduino IDE’s Serial Monitor	Figure 2.7: Nitinol wire and lever in reset position  

  	     (deformed state) 

 

Figure 2.8: Nitinol wire and lever in maximum shape recovery position at 55 degree opening gripper. 

Experiment 2: Evaluating Nitinol wire’s torque load capacity  

 

Step 1: Place the weighing scale next to the Nitinol wire and lever. Adjust the weighing scale until it is balanced. Long lever is used in this experiment. 

Step 2: Make sure the Nitinol wire is in reset position. Open Serial Monitor in Arduino IDE. 

Step 3: Using the previous experiments data, set the increment to 200 and press “1”. 

Step 4: When the Nitinol wire had reached its temperature in which to restore its original position (based on the previous experiment data), add weights until the weighing scale is balanced. 

Step 5: Record the weight needed to balance the weighing scale. 

Step 6: Press “0” to turn the voltage off and let the Nitinol wire cool down. 

Step 7: Calculating the torque produced using weight and torque formulas. 

 

		 

Figure 2.9: Weighing scale, Nitinol wire		Figure 2.10: Nitinol wire and lever in  Weights are added to balance the weighing scale.     maximum shape recovery position. 

and lever in reset position (deformed state) 

 

 

Experiment 3: Evaluating Nitinol Soft Actuator Grasping performance 

 

Step 1: Setup this experiment as below figure. 

 

Figure 2.11: Soft Actuator Gripper test setup. 

 

Step 2: Make sure the Nitinol wire is in reset position. Open Serial Monitor in Arduino IDE. 

Step 3: Using the previous experiments data, set the increment to 200 and press “1”. 

Step 4: Hold a small object in between the Soft Actuator gripper with your hand as shown in figure below. 

 

 

Figure 2.12: Soft Actuator Nitinol wire gripper ready for grasping object. 

 

Step 5: When the Nitinol wire had reached its temperature in which to restore its original position (based on the previous experiment data), release the small object from your hand. 

Step 6: Record the observation whether the small object is able to maintain grasp by the gripper.  

Step 7: Press “0” to turn the voltage off and let the Nitinol wire cool down. 

Step 8: Record the observations whether the small object is release from the gripper. 

Step 9: Weight the small object on the weighing scale.   

Step 10: Repeat Step 2 to Step 9 with another different small object. 

 

 

Results - Nitinol wire experiment as a soft actuator 

Experiment 1’s Result : Evaluating the temperature, voltage and current needed to deform and recover its original shape 

These are the experimental result’s graphs for evaluating the temperature and voltage needed to deform and recover its original shape.  

For the first experiment, we’ve conducted 6 attempts in total with variation of ambience temperature.  

 

 

 

From these 6 graphs, we can conclude that the time required for the Nitinol wire to deform is longer when the ambience temperature is higher. On the other hand, the difference in ambience temperature didn’t affect the voltage or current required for the Nitinol wire to restore its original shape.  It took about 3s to activate the Soft Actuator gripper into its transformed stated and another 5s to restore to its deformed state.  

For the second experiment, which is to evaluate the torque produced by Nitinol wire of a specific length and diameter. The table below shows the mathematical calculation to obtain the Nitinol wire’s torque. 

Experiment 2’s Result: Evaluating Nitinol wire’s torque   

 

 

Nitinol wire length: 0.1524m Diameter: 0.4mm 

 

 

Lever Length/Radius: 5.25x10^-3m 

 

Weight applied: 

14.8x10^-3kg 

 

 

 

 

 

 

Force: 

 

F=mg 

 

 

 

 

F=14.8x10^-3kg x 9.81ms^-1 

 

 

F=0.145188N 

 

 

 

 

 

 

Torque 

 

τ = rF 

 

 

 

 

τ=5.25x10^-2m x 0.125188N 

 

 

τ=6.57237x10^-3Nm 

 

By doing this experiment, we can come to a conclusion that a Nitinol wire with a length of 0.1524m and a diameter of 0.4mm is able to produce a force of 0.145188N which is comparable with lifting a Compact Disc that typically weighs 15 g. It produces a torque of 6.57237x10^-3Nm.	 

Experiment 3’s Result: Evaluating Nitinol Soft Actuator Grasping performance 

The torque produces by Nitinol wire is possible to grasp small object as long as the weight of the object is less than the Nitinol wire’s load capacity and the surface smoothness of the object. As the objects were getting heavier and its weight surpass the Nitinol wire’s load capacity, the object falls off the grip. Surprisingly a light weight object a ten cent coin fall off the gripper despite lighter than the load capacity. This is due to the friction force is lower than the grip surface capability.  

			 

Figure 2.13: Small object is placed in 		Figure 2.14: Small object is successfully 

between the soft actuator gripper.			   grasp by the soft actuator gripper.			 

Figure 2.15: Weight of this small object is 8.5g. 	      Figure 2.16:  Small object and their  

Soft Actuator is able to grasp an 8.5g object		success in grasping performance with the 

since it has a load capacity of 14.8gm force.		Soft Actuator gripper. 
