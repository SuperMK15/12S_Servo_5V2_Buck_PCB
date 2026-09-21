# 12S to Servo 5V2 Buck PCB

Custom Battery Eliminator Circuit (BEC) PCB built around the **LM65680RZYR** buck switching regulator IC, efficiently stepping down a 12S battery input (36V–50.4V) to 5.2V and supporting up to 8A of continuous draw for VTOL drone servo rails.

![Front View](images/Helios_12S_Servo_5V2_Buck_Front.png?v=2)
![Back View](images/Helios_12S_Servo_5V2_Buck_Back.png?v=2)

## Features

* Built around the LM65680RZYR buck switching regulator IC.
* 12S battery input supporting 36V to 50.4V via an XT30 male connector.
* 5.2V output supporting up to 8A maximum draw via an XT30 female connector.
* Input overvoltage protection utilizing an SMCJ54A TVS diode.
* Dedicated test point for Power Good (PG) monitoring.
* Two mounting holes, following a standard 30.5 × 30.5 mm M3 mounting pattern.

## PCB Layers

### Front Copper (Layer 1)

![Front Copper](images/Helios_12S_Servo_5V2_Buck-F_Cu.svg?v=2)

### Ground (Layer 2)

![Ground](images/Helios_12S_Servo_5V2_Buck-In1_Cu.svg?v=2)

### Ground (Layer 3)

![5.2 V](images/Helios_12S_Servo_5V2_Buck-In2_Cu.svg?v=2)

### Back Copper (Layer 4)

![Back Copper](images/Helios_12S_Servo_5V2_Buck-B_Cu.svg?v=2)

## Design Files

Designed in **KiCad 10**. Includes the complete schematic, PCB layout, custom footprints/symbols, and manufacturing files.
