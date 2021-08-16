# AX5043
Test board for the ON Semiconductor AX5043 RF transceiver chip

### Main differences between our board and other available out there
There are two major differences:
- the PWRAMP pin can be used as a sigma-delta modulator output for analog demodulation
- GPADC1 and GPADC2 pins can be used for analog frequency modulation (a VCO mode, if you will)

Note: There are no additional operational amplifiers nor filters in our design. Both modulator input and output are available at the pin header.
