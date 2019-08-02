# Car Sensor Board PCB Design Files


This project, part of a design competition run by Formula SAE, aims to develop a system that integrates various sensors and a communication channel to monitor the dynamic behavior of the tire and the suspension system in car and report them to a central unit for analysis to increase the stability of the car, hence it’s driver’s safety. This device will be mounted on the suspension arm which is connecting the tire to the car. This project included design, research and development components to prototype, code, fabricate and assemble the integrated system together. 
The system included a microcontroller, CAN Transceiver, gyroscope sensor, thermal infrared sensor, linear travel potentiometer and strain gauge load cell. Following the breadboard prototyping, a 2 layer printed circuit board was designed using an EDA and sent to a PCB manufacturer to be fabricated. The components and materials were assembled in a bill of materials and sourced through various electronics suppliers.

## Schematic Sheet
Application notes from data sheets and schematic references from development boards were used to assist in designing the schematics of the system. Some circuits like the op-amp buffers were suggested by Formula SAE to comply with the safety guidelines for automobile electrical engineering practices. 

![Schematic Sheet](schematic.png?raw=true "System")

## Stackup
Layer stack with 2 signal layers and a FR-4 dielectric prepreg as the core as shown in Figure 5. After the layer stack has been defined, a polygon pour was placed on the top and bottom layers corresponding to the GND and 5V respectively.  

![Stackup](stackup.png?raw=true "System")

## Routing and Component Placement
Track widths are adjusted according to the expected current going through it. Stitching vias were placed along the edge of the board to aid in noise reduction and finally non plated mounting holes were placed on the edges of the board.  Finally, to reduce the cost of prototypes, SMD test points were placed on the PCB board to help debug and find the issues quickly and reduce the prototyping cycle.

![Stackup](Routing.png?raw=true "System")
