# DerbyNet

[DerbyNet](https://github.com/jeffpiazza/derbynet) is open-source Pinewood Derby race management software that runs as a local web application and communicates with the timer over USB serial.

## Requirements

- Java 8+
- A modern web browser
- USB serial connection to the Arduino timer

## Timer Serial Settings

| Setting | Value |
|---------|-------|
| Baud rate | 9600 |
| Data bits | 8 |
| Parity | None |
| Stop bits | 1 |

## Setup

1. Flash `arduino/timer/timer.ino` to the Arduino.
2. Connect the Arduino to the host computer via USB.
3. Download and start DerbyNet from the [releases page](https://github.com/jeffpiazza/derbynet/releases).
4. Navigate to **Setup → Timer**, select the correct serial port, and click **Connect**.
