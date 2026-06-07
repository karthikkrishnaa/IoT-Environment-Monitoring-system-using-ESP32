# IoT-Environment-Monitoring-system-using-ESP32
The IoT-Based Environmental Monitoring System focused primarily on the design and development of a custom double-layer PCB using KiCad, covering schematic creation, footprint assignment, PCB layout, routing, ERC/DRC validation, and fabrication-ready design. The designed PCB was then integrated with an ESP32 microcontroller and environmental sensors to monitor parameters such as air quality, CO₂, temperature, humidity, and noise levels in real time. Sensor data was processed by the ESP32 and transmitted to a cloud platform via Wi-Fi for remote monitoring, while LED and buzzer alerts provided immediate notification of hazardous conditions.
## Block Diagram
The project workflow began with the design and fabrication of a custom double layer PCB using KiCad, ensuring accurate schematic representation, proper routing, and stable power distribution through a regulated supply. Embedded programming was carried out in the Arduino IDE using Embedded C, enabling the ESP32 to continuously acquire sensor data, display readings locally, and trigger alerts when thresholds were exceeded. The alert mechanism included LED blinking and buzzer activation, ensuring immediate response to hazardous conditions.
This project provided hands on experience in PCB design, sensor integration, and embedded programming, while also strengthening skills in debugging, validation, and real time system implementation. It demonstrated how IoT technologies can be applied to enhance situational awareness, improve public safety, and support environmental research.
Block Diagram (Description for Report)
The block diagram of the IoT Environmental Monitoring System consists of:
•	ESP32 Microcontroller at the core, handling sensor inputs and control logic.
•	Gas Sensors (MQ 7, MQ 135, MG 811) connected to analog/digital pins for pollutant detection.
•	DHT11 Sensor for temperature and humidity monitoring.
•	Sound Sensor for ambient noise measurement.
•	Alert Mechanism including LED and buzzer driven by ESP32 GPIO outputs.
•	Power Supply Section with a 12V input regulated by a 7805 IC to provide stable 5V and 3.3V rails.
•	Custom PCB with RMC connectors ensuring proper interfacing and reliable operation.
<img width="791" height="453" alt="image" src="https://github.com/user-attachments/assets/a3446ae7-4084-4bcf-a760-caa74ecb6022" />
### Circuit Diagram of IoT Monitoring system 
<img width="971" height="578" alt="image" src="https://github.com/user-attachments/assets/52f7beee-fd68-4e73-964a-0166fd74ccbf" />
#### PCB layout and 3D model in kicad
<img width="804" height="533" alt="image" src="https://github.com/user-attachments/assets/c0ac0169-c6d0-4d2d-91c9-b01daee69521" />
<img width="804" height="533" alt="image" src="https://github.com/user-attachments/assets/eab2d018-8382-40e3-8311-225b5cd81093" />
<img width="780" height="405" alt="image" src="https://github.com/user-attachments/assets/0ee96233-c69d-4716-90c9-2cb5e9a8affd" />
<img width="633" height="373" alt="image" src="https://github.com/user-attachments/assets/0b6a4200-d414-49e3-a90f-ce39f1d9a71c" />

Finally, real world testing was conducted by deploying the system in an actual environment. The board was powered continuously, and sensor readings were monitored for long term stability. The results confirmed that the PCB design was robust, the sensors were accurately integrated, and the ESP32 firmware operated reliably. Cloud connectivity remained stable, and the Thing Speak dashboard provided clear visualization of environmental parameters. Overall, the testing and analysis phase validated the effectiveness of the design and demonstrated that the project objectives were successfully achieved.
The figure illustrates a custom fabricated two layer printed circuit board (PCB) designed for sensor interfacing and embedded system applications. The board is manufactured on a green substrate with copper traces carefully routed to support multiple through hole components and connectors. Four mounting holes are positioned at the corners to provide mechanical stability during enclosure integration. The PCB layout demonstrates organized rows of through hole pads, enabling flexible component placement and sensor connectivity. Copper routing is optimized to ensure reliable signal flow.
##### Fabricated PCB of the project
<img width="669" height="475" alt="image" src="https://github.com/user-attachments/assets/5f93defb-e93b-4831-b457-bfaa8c54c2b8" />
<img width="676" height="436" alt="image" src="https://github.com/user-attachments/assets/0dcf01b0-8add-4893-b9d7-6a87f796210a" />


