# Arduino LED Blinking QA Project

## Objective

The objective of this project is to control an LED using an Arduino Uno
and make it blink continuously at a fixed interval.

## Components Used

- Arduino Uno
- LED
- 220Ω resistor
- Breadboard
- Jumper wires

## Working

The LED is connected to digital pin 8 of the Arduino.
The program configures digital pin 8 as an output and repeatedly
switches the LED ON and OFF.

The LED remains ON for 500 milliseconds and OFF for 500 milliseconds.

## Expected Output

The LED should blink continuously with equal ON and OFF intervals.

## QA Testing

The project is checked for:

- LED connection
- GPIO pin configuration
- Blinking timing
- Current limiting resistor
- Program compilation
- Power connection

## QA Documentation

GitHub Issues are used to record QA problems and document their
resolution. Commits and branches are used to maintain project history
and track corrective changes.
