# Arduino Air Quality Detection with MQ-135 Sensor

This project implements air quality detection using an MQ-135 gas sensor and displays the air quality status on an OLED screen. The system calculates air quality based on the resistance measured by the sensor and provides a visual indication of air quality.

## Components

- Arduino board (e.g., Arduino Uno)
- MQ-135 gas sensor
- OLED display (e.g., SSD1306)
- Jumper wires

## Features

- Real-time air quality monitoring
- OLED display for visual indication
- Adjustable air quality thresholds

## Setup

1. Connect the components to your Arduino board following the wiring instructions in your Arduino sketch.

2. Upload the provided Arduino code to your board.

## Configuration

- The code includes a `calculateAirQuality` function that converts sensor values into an air quality index. You can adjust the `zeroValue` and `minValue` based on your sensor's characteristics for accurate readings.

## Usage

1. Power on the system.

2. The OLED display shows real-time air quality information:
   - "Good" air quality: Air quality is within acceptable levels.
   - "Poor" air quality: Ventilate or take appropriate action.

## Dependencies

- This project uses the Adafruit SSD1306 library to work with the OLED display. Ensure you have this library installed in your Arduino IDE.

## Authors

- [Santhosh]
