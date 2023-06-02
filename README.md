# Avionics PCB Design

This is the PSPHA Avionics PCB design. It uses an ATtiny MCU, Barometer, IMU to measure flight data and record it to a flash memory chip.

## Pin Map

| Port | Pin 1 | Pin 2            | Pin 3        | Pin 4        | Pin 5        | Pin 6        |
| ---- | ----- | ---------------- | ------------ | ------------ | ------------ | ------------ |
| J1   | GND   | SCLK             | MISO         | MOSI         |              |              |
| J2   | GND   | PA7              |              |              |              |              |
| J3   | GND   | Vin (5 V to 9 V) | Recovery 2 + | Recovery 1 + | Recovery 2 - | Recovery 1 - |
| J4   | GND   | TOSC1            | TOSC2        |              |              |              |
| J5   | GND   | UPDI             |              |              |              |              |
| J6   | GND   | GND              | GND          | 3.3 V        |              |              |
