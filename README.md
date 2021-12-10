# AX5x43
Test boards for the ON Semiconductor AX5043 and AX5243 RF transceiver chips.
#### The main purpose of this board is to test AX5x43's M17 support.

### Main differences between our board and other available out there
There are two major differences:
- the PWRAMP (AX5043) or TCXO_EN (AX5243) pin can be used as a sigma-delta modulator output for analog demodulation
- GPADC1 and GPADC2 pins can be used for analog frequency modulation (a VCO mode, if you will)

Note: There are no additional operational amplifiers nor filters in our design. Both modulator input and output are available at the pin header. ADC inputs can work in both differential and single-ended modes. Refer to the application note [AND9313/D](https://www.onsemi.com/pub/collateral/and9313-d.pdf).

### PCB
![PCB](https://user-images.githubusercontent.com/44336093/145544711-7f87339f-ce2f-40c3-93e1-8d97b13a539c.png)
