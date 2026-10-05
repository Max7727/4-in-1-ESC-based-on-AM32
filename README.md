


# 4-in-1 ESC based on AM32
32-bit 4-in-1 FPV Drone ESC (Active Development)

Custom 32-bit 4-in-1 Electronic Speed Controller (ESC) tailored for a 6S battery-powered 5-inch FPV quadcopter. 

Features:
* A robust power management tree stepping down 6S voltage to 8V via a SY8303 synchronous buck converter for gate drivers, and further to 3.3V via a CJA1117B LDO for the main MCU. 
* A sensorless back-EMF zero-crossing detection circuit and a 3-phase inverter bridge utilizing NTMFS5C410NL MOSFETs. 
* Four independent FD6288Q half-bridge gate drivers, an AT32F421K8U7 ARM Cortex-M4 microcontroller running AM32 firmware, and an INA199 bidirectional current shunt monitor. 


The PCB layout for this design is currently in active development.


The end goal of this project is to design and manufacture ESC pcb, that can be connected to online-bought flight controler.


# Schematics
### Power delivery
<img src="\Outputs/Screenshot1.png" >

### Motor Gate Drivers
<img src="\Outputs/Screenshot_2.png" >
<img src="\Outputs/Screenshot_3.png" >



# PCB
### PCB layout is not ready. The PCB layout for this design is currently in active development. 
Example of how ESC should look like:

<p align="center">
    <img src="\Outputs/71JCXNh9OwL._AC_UF894,1000_QL80_.png" width="35%">
</p>




Altium 25.8.1