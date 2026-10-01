# ESP32 OLED Display with LDR

## Project Description

This project demonstrates interfacing an LDR (Light Dependent Resistor) with an ESP32 and displaying its live sensor reading on an SSD1306 OLED display.

The LDR senses the surrounding light intensity. The ESP32 reads the analog value from the LDR and displays the live reading on the OLED screen.

## Components Used

- ESP32
- LDR (Light Dependent Resistor)
- SSD1306 OLED Display
- Resistor
- Wokwi Simulator

## Connections

### LDR

- LDR VCC → ESP32 3V3
- LDR GND → ESP32 GND
- LDR SIG → ESP32 GPIO 34

### SSD1306 OLED

- OLED VCC → ESP32 3V3
- OLED GND → ESP32 GND
- OLED SDA → ESP32 GPIO 21
- OLED SCL → ESP32 GPIO 22

## Working

1. The LDR senses the surrounding light intensity.
2. The ESP32 reads the analog value from the LDR.
3. The sensor value is continuously updated.
4. The ESP32 sends the LDR reading to the SSD1306 OLED display.
5. The live sensor reading is displayed on the OLED screen.
6. When the light intensity changes, the displayed value also changes.

## OLED Display

The SSD1306 OLED display is used to show the live LDR sensor reading in real time.

## Applications

- Light intensity monitoring
- Automatic lighting systems
- Smart home systems
- IoT projects
- Environmental monitoring
- Embedded systems

## Simulation

https://wokwi.com/projects/476655570621966337
