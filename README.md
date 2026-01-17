
#CSCE 838: Cyber-Physical Systems and Internet of Things - Fall 2024

A collection of IoT lab assignments exploring embedded systems programming, wireless communication, and cloud integration.

## Labs

### Lab 2: LED Control & Timing
Introduction to Arduino programming with non-blocking LED control patterns.
- Multi-LED timing with independent intervals
- Non-blocking code using `millis()`
- Serial communication for debugging

**Directory:** `lab2/`

### Lab 3: IoT System Integration
Multi-node wireless sensor network using SparkFun ProRF boards.
- RF95 LoRa radio communication at 902MHz
- Temperature sensor data collection and averaging
- Multi-node mesh network (4 nodes)
- Watchdog timer (WDT) implementation
- Flash storage for data persistence
- Error detection and packet loss tracking

**Directory:** `lab3/`

### Lab 4: Sensor Data Processing
Advanced sensor data handling and reporting.

**Directory:** `lab4/`

### Lab 5: Connecting IoT to the Cloud with Microsoft Azure
Cloud integration using Azure IoT services.
- Azure IoT Hub/Central connectivity
- Telemetry data streaming
- Cloud-based device management

**Directory:** `Lab5/`

### Lab 6: Automating Things
IoT automation with machine learning integration.
- Azure Functions for serverless computing
- Python-based IoT device communication
- ML model integration for sensor data prediction
- Automated telemetry processing

**Directory:** `lab6/`

## Technologies Used
- Arduino (SAMD21 microcontroller)
- SparkFun ProRF (LoRa RF95)
- C++ (Arduino sketches)
- Python
- Microsoft Azure (IoT Hub, IoT Central, Functions)
- RadioHead Library
- TemperatureZero Library

## Hardware
- SparkFun SAMD21 Pro RF boards
- Built-in temperature sensors
- LoRa radio modules (902-928 MHz)
