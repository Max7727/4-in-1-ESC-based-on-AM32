


# 4-in-1 ESC based on AM32
32-bit 4-in-1 FPV Drone ESC (Active Development)

Custom 32-bit 4-in-1 Electronic Speed Controller (ESC) meant for a 6S battery-powered 5-inch FPV quadcopter. 


### The end goal of this project is to design and manufacture ESC pcb, that can be connected to online-bought flight controler.


Features:
* The AM32 Open Source firmware, users can modify and customize it themselves according to their needs. https://github.com/AlkaMotors/AM32-MultiRotor-ESC-firmware
* Power management stepping down 6S voltage to 8V via a SY8303 buck converter for gate drivers, and further to 3.3V via a CJA1117B LDO. 
* A sensorless back-EMF zero-crossing detection circuit and a 3-phase inverter bridge utilizing NTMFS5C410NL MOSFETs.
* Four independent FD6288Q half-bridge IC gate drivers, designed for high-voltage, high-speed drive MOSFETs.
* AT32F421K8U7 ARM Cortex-M4 120MHz microcontroller running AM32 firmware.
* An INA199 current shunt monitor (on-board galvanometer). 
* Support a variety of motor protocols: servo PWM, Dshot300, Dshot600.
* Popular JSH-SH connector for flight controller.

The PCB layout for this design is currently in active development.


# Schematics
### Power delivery
<img src="\Outputs/Screenshot1.png" >

### Motor Gate Drivers

Motor M1
<img src="\Outputs/Screenshot_2.png" >

Motor M2
<img src="\Outputs/Screenshot_3.png" >
<img src="\Outputs/Screenshot_4.png" >

Motors 3 and 4 likewise

# Entire schematics
<img src="\Outputs/Entire schematics.png" >



# PCB
### PCB layout is not ready. The PCB layout for this design is currently in active development. 
Example of how ESC PCB will look like:

<p align="center">
    <img src="\Outputs/71JCXNh9OwL._AC_UF894,1000_QL80_.png" width="35%">
</p>


