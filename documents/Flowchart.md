## Flowchart of the Project

Start
  │
  ├───> [Room Modules] ──> [Sensors (Temperature, Humidity, etc.)] ──> [ESP32 Device]
  │                                     │
  │                                     └──> [Data Processing (ADC, I2C, SPI, etc.)]
  │
  ├───> [Room Modules] ──> [Wi-Fi Communication] ──> [Central Dashboard] ──> [Central Display]
  │                                     │                 (Local Display)
  │                                     └──> [Real-Time Data Update]
  │
  ├───> [Central Dashboard] ──> [RTOS] ──> [Task Scheduling (Data Collection, Display Updates)]
  │
  ├───> [Aquarium Module] ──> [Sensors (Water Temperature, pH)] ──> [ESP32 Automation] ──> [Automation Logic (Pump Control)]
  │
  ├───> [Plant Module] ──> [Sensors (Soil Moisture)] ──> [ESP32 Automation] ──> [Automation Logic (Watering Control)]
  │
  ├───> [Room Data] ──> [Wi-Fi Communication] ──> [Web App Server]
  │                      │                             │
  │                      └──> [MQTT/HTTP] ──> [Real-Time Data Sync to Web App]
  │
  ├───> [Web App] ──> [Frontend Display (HTML, CSS, JS)] ──> [Real-Time Data View]
  │                      │                             │
  │                      └──> [Control Interface] ──> [User Actions (Control Devices)]
  │
  └───> End
