# twiboot - a TWI / I2C bootloader for AVR MCUs ##

fork of the [twiboot](https://github.com/orempel/twiboot) bootloader with following modifications:
- ATtiny84 support only
- LED_SUPPORT set to 0
- Makefile modified to set TWI_ADDRESS on make call: `make ADDRESS=0x0F`
