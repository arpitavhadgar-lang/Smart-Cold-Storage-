# ESP32 Control Code

This folder contains the ESP32 program used for monitoring and
controlling the Climate-Adaptive Solar Smart Mini Cold Storage system.

## Functions

The ESP32 is responsible for:

- Reading temperature and humidity sensor data
- Monitoring storage conditions
- Comparing the measured temperature with the defined threshold
- Controlling the DC cooling system
- Generating alerts during abnormal conditions
- Monitoring the system continuously

## Control Logic

The basic control sequence is:

1. Initialize the ESP32 and connected sensors.
2. Read temperature and humidity values.
3. Compare the measured temperature with the predefined threshold.
4. Keep active cooling OFF when the temperature is within the desired
   range.
5. Activate active cooling when the temperature exceeds the threshold.
6. Continue monitoring the storage conditions.
7. Generate an alert if an abnormal temperature condition persists.

## Development Environment

- Microcontroller: ESP32
- Programming Environment: Arduino IDE
- Programming Language: Embedded C/C++
