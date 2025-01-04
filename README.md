# Home-device-control-via-IR-Remote

This project demonstrates how to control home devices using an IR (Infrared) remote and an Arduino Uno. It provides a simple and cost-effective solution for remote-controlled automation of home appliances.

## Features

- Control multiple home devices with an IR remote.
- Customizable IR button-to-action mappings.
- Includes circuit diagrams and source code for easy setup.
- Supports serial port monitoring for debugging.

## Project Components

- **Hardware**:
  - Arduino Uno
  - IR Receiver Module
  - Home Appliances (e.g., LED, fan)
  - Resistors and connecting wires
- **Software**:
  - Arduino IDE
  - Provided Arduino sketch (`IR.ino`)

## Project Structure

```
Home-device-control-via-IR-remote-master/
├── .gitignore                   # Git ignore rules
├── Demo Video.mp4               # Video demonstrating project functionality
├── README.md                    # Project documentation
├── arduino uno board diagram.png    # Arduino pin diagram
├── project circuit diagram.png      # Circuit diagram for connections
├── serial port monitor.png          # Serial monitor output example
├── used IR remote and button values.png # Button mappings for the IR remote
└── IR Code/
    ├── IR.ino                  # Arduino sketch
    └── IR_code.txt             # Additional code notes or configurations
```

## Circuit Diagram

![project circuit diagram](https://github.com/user-attachments/assets/4f742d50-70d7-4a51-b1e4-dc931d4accbd)


## Getting Started

### Prerequisites

1. Install the [Arduino IDE](https://www.arduino.cc/en/software/).
2. Set up the hardware as per the provided circuit diagram.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Home-device-control-via-IR-remote.git
   ```
2. Open the `IR.ino` file in the Arduino IDE.
3. Upload the code to your Arduino Uno.

### Customizing IR Codes

1. Use the `used IR remote and button values.png` to understand the pre-mapped values.
2. Modify the `IR.ino` file to adjust the actions mapped to specific IR buttons.

## Demo

[Demo Video](Demo%20Video.mp4)





