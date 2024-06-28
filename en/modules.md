# Modules

| Module                   | Specification                | Function                                                                                                    | Note                               |
| ------------------------ | ---------------------------- | ----------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| Main Unit                | Based on ESP32-D0WD-V3       | Core Module                                                                                                 |                                    |
| OBD Adapter              | BT3.0 or BLE                 | Used for communication between ADU and vehicle                                                              | Recommended for Vgate iCar Pro BLE |
| Main Display Module      | 1.6" 130\*130 TFT sun screen | Used for main display                                                                                       |                                    |
| Secondary Display Module | 1.3" 128\*32 OLED            | Used for additional display                                                                                 |                                    |
| Environment Sensor       | SHT30 + QMP6988              | Used for ambient temperature, humidity and atmospheric pressure                                             |                                    |
| Gyro Module              | WitMotion JY61P              | Used for measuring the vehicle's pitch (gradient) and roll angle                                            | Soldered inside the main unit      |
| GPS Module               |                              | Used for GPS positioning, obtaining vehicle GPS speed, altitude, position, direction and other information. |                                    |
| Light Sensor             |                              | Used for automatically adjusting the brightness of the display according to the ambient light intensity.    |                                    |
| Button                   |                              | Used for switching the display interface and adjusting the settings                                         |                                    |
| Cables                   |                              | Used for connecting the main unit to external modules                                                       |                                    |
