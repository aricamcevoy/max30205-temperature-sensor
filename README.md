## Project Overview

Reading temparature data from a MAX30205 sensor using an Arduino Mega via I2C.

## What I built

- Established I2C communication
- Detected device at address 0x48
- Read raw temperature data and converted to Celsius/Fahrenheit

## Challenges

- Initally received I2C error 2 (no ACK)
- Used I2C scanner to diagnose connection
- Discovered intermittent connection due to unsoldered header pins
- Confirmed by applying pressure to module

## Lessons Learned

- Hardware issues can mimic software bugs
- I2C requires stable physical connections
- Always verify device detection before debugging logic

# Next Steps

- Solder h3eqader pins for stable readings
- Add averaging/filtering to stablize output
- Integrate into BBT tracking system
