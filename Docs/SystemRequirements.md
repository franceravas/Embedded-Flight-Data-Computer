# Flight Computer Requirements

## Functional Requirements

The board shall:

- Read IMU data over SPI.
- Read GPS data over UART.
- Log data to a microSD card.
- Blink a heartbeat LED.
- Be programmable using SWD.
- Operate from USB power.

## Performance Requirements

- IMU update rate: 100 Hz
- GPS update rate: 10 Hz
- UART debug baud rate: 115200

## Constraints

- STM32 microcontroller
- Designed in KiCad
- Firmware written in C
- Version controlled using Git

## Future Improvements

- Barometer
- Magnetometer
- LoRa Radio
- CAN Bus