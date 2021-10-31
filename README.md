# AX5x43
Test boards for the ON Semiconductor AX5043 and AX5243 RF transceiver chips.
#### The main purpose of this board is to test AX5x43's M17 support.

### Main differences between our board and other available out there
There are two major differences:
- the PWRAMP pin can be used as a sigma-delta modulator output for analog demodulation
- GPADC1 and GPADC2 pins can be used for analog frequency modulation (a VCO mode, if you will)

Note: There are no additional operational amplifiers nor filters in our design. Both modulator input and output are available at the pin header. ADC inputs can work in both differential and single-ended modes. Refer to the application note [AND9313/D](https://www.onsemi.com/pub/collateral/and9313-d.pdf).
