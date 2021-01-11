# Multiprotocol_via_ble
BLE to I2C SPI UART GPIO ADC communication

# Features
Crossed out features not implemented yet

* BLE to UART
* ~~BLE to I2C~~
* ~~BLE to SPI (one CS)~~
* ~~BLE to GPIO out x2~~
* ~~BLE to GPIO IN x2~~
* ~~BLE to ADC x2~~

# Hardware
Using NRF52840 dongle on the custom PCB

## Pinout

### I2C
* 0.13 - SDA
* 0.15 - SCL

### UART
* 0.17 - RX
* 0.18 - TX

### GPIO
* 0.22 - GPIO0 OUT
* 0.24 - GPIO1 OUT
* 0.09 - GPIO2 IN
* 0.10 - GPIO3 IN

### ADC
* 0.31 - ADC1
* 0.29 - ADC2

### SPI
* 1.00 - CS
* 1.15 - MISO
* 1.13 - MOSI
* 1.10 - CLCK

### Spare
* 0.02 - ???

# Software
Zephyr NCS 1.4.1




