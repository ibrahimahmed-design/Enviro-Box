# EnviroBox

**EnviroBox** Is A smart, open-source, portable device designed to monitor indoor air quality in real time without an internet connection. Ideal for classrooms and homes. It features a visual and audible alarm system when fault indicators are detected.
##  Overview

EnviroBox measures:
- **CO₂ (Carbon Dioxide)**
- **PM2.5 (Fine Dust Particles)**
- **CO (Carbon Monoxide)**
- **Temperature, Humidity, and Pressure**

 Data is displayed on a screen. When dangerous levels are detected, it activates both visual (RGB LEDs) and audible (buzzer) alarms.

 The device works by connecting it to a power bank or battery via USB Type-C.

##  Why it Matters

Indoor air quality has a huge impact on focus, health, and wellbeing—especially in schools and densely populated areas.  
Commercial solutions are often expensive and closed-source.

EnviroBox offers:
- An affordable, DIY alternative.
- Open-source code and schematics.
- Educational value for students and makers.

##  Components & Cost

| Name                           | Function                                   | Estimated Price (USD)     |
| ------------------------------ | ------------------------------------------ | ------------------------- |
| ESP32-S3-DEVKITC               | Main microcontroller for logic and control | 33                        |
| USB-C Connector                | Power input                                | 26                        |
| SCD40-D-R2                     | CO₂                                        | 29                        |
| ZPH02                          | PM2.5 air quality sensor                   | 36                        |
| ZE07-CO                        | Carbon monoxide (CO) gas sensor            | 31                        |
| BME280                         | Temperature, humidity, and pressure sensor | 34                        |
| 1.3" OLED (7P)                 | Display environmental data                 | 23                        |
| RGB LED (8028)                 | Visual status indicator                    | 6                        |
| W25Q64 (SPI Flash)             | Data logging / storage                     | 32                        |
| Buzzer 12x9mm                  | Audible alert / notification               | 4                        |
| 220Ω Resistors ×3              | Current limiting for LEDs/Buzzer           | 12                        | 
| PCB                            | Custom circuit board                       | 15              |
| 3D Printed Case                | Enclosure for protection                   | 12 (material cost)        |
| Li-ion Battery                 | Portable power supply                      | 27                        |
| Misc. (Wires, headers, screws) | Assembly and connectivity                  | 10                        |

###  **Total Cost: $330**

##  Features

- Accurate air quality measurement (carbon dioxide, PM2.5, and carbon monoxide)
- Environmental monitoring (temperature, humidity, pressure)
- Real-time data display with color-coded alerts
- Local data recording to SD card
- Battery or power bank
- Compact and portable design
- Open source code and schematics

##  Alert System

-  Green: Safe
-  Yellow: Warning
-  Red: Hazard – activates buzzer

Buzzer emits different tones based on the detected pollutant (CO, CO₂, or PM2.5).

##  Timeline

| Week | Tasks |
|------|-------|
| 1 | Order components, test main sensors +  Connect sensors to ESP32, display & alert testing |
| 2 | Integrate battery + solar, assemble in enclosure + Optimize code, run performance tests, publish documentation |

##  Community Impact

- Raise awareness of air pollution, especially in schools
- Low-cost, replicable, and educational for students
- Promotes hands-on learning and DIY mindset


##  Media (coming soon)

-schematic,PCB layout and wiring diagram
![](https://github.com/ibrahimahmed-design/Enviro-Box/raw/main/images/WhatsApp%20Image%202025-05-30%20at%2010.52.49%20AM.jpeg?raw=true)
![](https://github.com/ibrahimahmed-design/Enviro-Box/blob/main/images/WhatsApp%20Image%202025-05-30%20at%2010.52.49%20AM%20(4).jpeg?raw=true)
- Onshape design of the enclosure
![](https://github.com/ibrahimahmed-design/Enviro-Box/blob/main/images/WhatsApp%20Image%202025-05-30%20at%2010.52.49%20AM%20(5).jpeg?raw=true)
![](https://github.com/ibrahimahmed-design/Enviro-Box/blob/main/images/WhatsApp%20Image%202025-05-30%20at%2010.52.49%20AM%20(6).jpeg?raw=true)
![](https://github.com/ibrahimahmed-design/Enviro-Box/blob/main/images/WhatsApp%20Image%202025-05-30%20at%2010.52.49%20AM%20(7).jpeg?raw=true)
![](https://github.com/ibrahimahmed-design/Enviro-Box/blob/main/images/WhatsApp%20Image%202025-05-30%20at%2010.52.49%20AM%20(8).jpeg?raw=true) 
![](https://github.com/ibrahimahmed-design/Enviro-Box/blob/main/images/WhatsApp%20Image%202025-05-30%20at%202.11.49%20PM.jpeg?raw=true)

##  Progress Journal

Check out [`JOURNAL.md`](./JOURNAL.md) for regular project updates.

