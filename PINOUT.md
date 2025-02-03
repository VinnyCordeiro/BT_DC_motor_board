# Pinout:

## Endstops

|Endstop|RPi Pico*|Black Pill|
|-------|---------|----------|
|1|gpio22|PA5|
|2|gpio20|PA3|
|3|gpio18|PA1|
|4|gpio16|PC15|
|5|gpio13|PB9|
|6|gpio15|PC13|
|7|gpio26|PA6|
|8|gpio21|PA4|
|9|gpio19|PA2|
|10|gpio17|PA0|
|11|gpio12|PB8|
|12|gpio14|PC14|

## CAN bus

|Function|RPi Pico*|Black Pill|
|--------|---------|----------|
|CAN-TX|gpio27|PA7|
|CAN-RX|gpio28|PB0|

## DC motors

### Motor 1

|Function|RPi Pico*|Black Pill|
|--------|---------|----------|
|SLP_1|gpio0|PB12|
|DC1_1|gpio1|PB13|
|DC2_1|gpio2|PB15|

### Motor 2

|Function|RPi Pico*|Black Pill|
|--------|---------|----------|
|SLP_2|gpio3|PA8|
|DC1_2|gpio4|PA9|
|DC2_2|gpio5|PA10|

### Motor 3

|Function|RPi Pico*|Black Pill|
|--------|---------|----------|
|SLP_3|gpio11|PB7|
|DC1_3|gpio10|PB6|
|DC2_3|gpio9|PB5|

### Motor 4

|Function|RPi Pico*|Black Pill|
|--------|---------|----------|
|SLP_4|gpio8|PB4|
|DC1_4|gpio7|PB3|
|DC2_4|gpio6|PA15|

\* While this board was designed using the original Raspberry Pi Pico, it _should_ work with the Raspberry Pi Pico 2, which uses the RP2350A MCU.
