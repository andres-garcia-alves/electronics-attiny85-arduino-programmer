# ATtiny85 Arduino Programmer

Electronic proyect to turn an Arduino Nano/UNO into an ATtiny85 programmer.  

Based on video [CREA tu Programador DIY para ATTINY85 con Arduino UNO](https://www.youtube.com/watch?v=IFw5A_K7DOM) (spanish) from [Kriss Electronics](https://www.youtube.com/@KrissElectronics) YouTube channel.

&nbsp;

This project use the following electronic components:
- 1 x Arduino Nano v3.0 (or Arduino UNO)
- 1 x Atmel ATtiny85
- 1 x Capacitor 10uF/16V
- 2 x 1-pin header
- 2 x 2-pins header
- 1 x 3-pins header

Notes:
- PCB pin-headers 5V-GND-RST-10-11-12-13 allows to program the ATtiny85 from an Arduino UNO, instead of Arduino Nano.
- Remove from PCB any pluged Arduino Nano if you are going to program the ATtiny85 from Arduino UNO pin-headers.
- Please refer to above video, to learn about requiered Arduino IDE configuration and programming process.

&nbsp;

### Screenshots

| Breadboard                                         | PCB Manufacturing                                  |
|----------------------------------------------------|----------------------------------------------------|
| ![](Resources/01-breadboard-01.jpg)                | ![](Resources/02-pcb-manufacturing-01.jpg)         |

| PCB Assembly                                       | PCB Assembly                                       |
|----------------------------------------------------|----------------------------------------------------|
| ![](Resources/03-pcb-assembly-01.jpg)              | ![](Resources/03-pcb-assembly-02.jpg)              |

| Schematics Diagram                                 | PCB Layout                                         |
|----------------------------------------------------|----------------------------------------------------|
| ![](Resources/04-schematic-diagram.png)            | ![](Resources/05-pcb-layout.png)                   |

| PCB 3D Render                                      | PCB 3D Render                                      |
|----------------------------------------------------|----------------------------------------------------|
| ![](Resources/06-pcb-render-front.png)             | ![](Resources/06-pcb-render-bottom.png)            |

| Case 3D Model                                      | Project Final                                      |
|----------------------------------------------------|----------------------------------------------------|
| ![](Resources/07-case-3d-model.jpg)                | ![](Resources/08-project-final.jpg)                |

See 'Rescources' sub-folder for more pictures & videos of the project.

&nbsp;

### Version History

v1.0 (2023.05.26) - Initial release.  
v1.1 (2023.05.29) - Optimizing PCB size.  
v1.2 (2023.05.31) - Fixed PCB bug.  
v1.3 (2025.12.30) - Update project structure.  
v1.4 (2026.01.12) - Minor PCB improvements.  
v1.5 (2026.01.16) - Adding case 3D model.  

&nbsp;

This source code is licensed under GPL v3.0  
Please send me your feedback about this project: andres.garcia.alves@gmail.com
