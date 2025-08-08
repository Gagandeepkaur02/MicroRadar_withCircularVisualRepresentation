# MicroRadar_withCircularVisualRepresentation
Real-time radar simulation using Arduino &amp; Processing. Visualizes ultrasonic sensor data as a sweeping radar with distance arcs.

**Arduino Ultrasonic Radar**
 
A real-time radar-style visualization built with **Arduino** and **Processing**.  
This project reads data from an **HC-SR04 Ultrasonic Sensor** connected to Arduino and displays it on a radar-like interface in Processing.

**Features**
- Sweeping radar line visualisation
- Displays object distance and angle
- Real-time data from ultrasonic sensor
- Customizable display colors and labels
- Distance arcs and angle markers

**Hardware Required**
- Arduino Uno / Nano / Mega
- HC-SR04 Ultrasonic Sensor
- Servo Motor (for scanning)
- Jumper wires
- Breadboard (optional)

## Software Required
- Arduino IDE:- https://www.arduino.cc/en/software
- Processing IDE:- https://processing.org/download/

## Wiring
| HC-SR04 Pin | Arduino Pin |
|-------------|------------|
| VCC         | 5V         |
| GND         | GND        |
| TRIG        | D10        |
| ECHO        | D11        |
| Servo Signal| D9         |

## Arduino Code
Upload the Arduino sketch (`ultrasonic_radar.ino`) to your board.  
The Arduino will send serial data in the format:
