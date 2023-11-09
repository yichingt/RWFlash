# RWFlash
SPI flash memory utility to read and write to the flash <br>
This program have references from the Raspberry Pi Pico pico-example <i>spi_flash</i>

## SPI Flash
### Wiring Information
Wiring up the SPI Flash to the pico with 6 jumper wires are as follows:
| PICO -> SPI External Flash |
* 3.3v   (pin 36)  -> VCC
* GPIO 4 (pin 6)   -> DO
* GPIO 5 (pin 7)   -> CS
* GPIO 2 (pin 4)   -> SCK
* GPIO 3 (pin 5)   -> DI
* GND (any GND pin) -> GND
