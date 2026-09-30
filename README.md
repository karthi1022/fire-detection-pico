# Real-Time Fire Detection System (Raspberry Pi Pico W)

An embedded edge-detection safety system deployed on Raspberry Pi Pico W to identify flame/fire triggers in real-time and actuate emergency GPIO controls.

## Hardware & Components
- Microcontroller : Raspberry Pi Pico W 
- Camera: OV7670 
- Actuators: Buzzer, Emergency Safety Relay, Status LEDs

## Tech Stack & Communication
- Languages: Python,Embedded C
- Firmware Engine: Thonny IDE 
- Communication: Wi-Fi (Pico W onboard) for wireless alert notifications
- Hardware Interface: SPI / I2C / GPIO

## Key Features
- Low-power edge processing for rapid flame/fire threshold detection.
- Instant hardware-level GPIO interrupt triggers for safety cutoff.
- Wireless Wi-Fi alert dispatch via onboard Pico W wireless chip.
