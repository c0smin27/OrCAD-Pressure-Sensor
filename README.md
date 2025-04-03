# OrCAD – Pressure Sensor Project

## Circuit Description

This project involves designing a pressure control system for a hyperbaric chamber. <br>
The pressure sensor used in the system can measure pressure linearly in the range of **1050-1530 mBar**. <br>
<br>
The system is designed to maintain the pressure inside the hyperbaric chamber within the range of **1200-1400 mBar**. <br>
The pressure sensor is current-biased, and its electrical resistance varies linearly from **20kΩ-25kΩ** depending on pressure. This resistance variation must be converted into a voltage range of **0V-12V**, with a supply voltage of **Vcc=14V**. <br>
<br>
Pressure control is achieved through a **pump**, which is activated or deactivated using a **comparator** and an **electromagnetic relay**. The pump-relay assembly is modeled using a resistor. <br>
The operational status of the pump (on/off) is indicated by a **blue LED**. <br>

## File Structure
<pre>
project/
 └─ PROIECT.DSN
 └─ proiect.opj
 └─ blue_led.ind
 └─ blue_led.lib
 └─ proiect-PSpiceFiles/
      └─ simulation
           └─ SCHEMATIC1.ALS
           └─ SCHEMATIC1.net
           └─ SCHEMATIC1.sch.prp
           └─ simulare1.sim
</pre>

![](https://raw.githubusercontent.com/c0smin27/OrCAD-Pressure-Sensor/refs/heads/main/readme.png)

## Disclaimer
This project was created as part of an academic assignment. Feel free to use it for learning purposes, but please do not submit it as your own work in educational settings.
