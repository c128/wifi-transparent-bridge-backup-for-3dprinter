ESP8266 transparent bridge backup for 3dprinter 

backup working firmware for ESP8266 512K 	

standard setting:
BAUD=500000 8 N 1 serial speed
ssid:3D_PRINTER
PASSWORD: 12345678


original firmware https://github.com/beckdac/ESP8266-transparent-bridge


upload firmware with nodemcu and this settings:
menu advanced
baud rate: 230.400 (or 115200)
flash size: 512k
flash speed: 40mhz
spi mode: DIO

menu Config
start address 0x00000
