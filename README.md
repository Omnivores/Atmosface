# Atmosface - interactive artwork
### *Concept and design by Omnivores Collective*
##### *3D model and design - Quique Valido*
##### *Sound design - Luca Morino*
##### *Electronics and Arduino programming - Giovanni Bologni and Francesco Cretti*
##### *August 2018*

## Equipment:
* Arduino Nano
* Cypress CY8CMBR3110 chip
* 10 Capacitive buttons
* Raspberry Pi 3 with PureData
* Audio speakers

## Technical details
Arduino sends to PureData three data types trough serial port.
* 2 proximity sensors. Values in range 0-65535
* 1 array of 10 capacitive touch buttons (1 touched, 0 not touched)


Buttons array order

PS0 | PS1 | CS5 | CS6 | CS7 | CS8 | CS2 | CS9 | CS3 | CS4
--- | --- | --- | --- | --- | --- | --- | --- | --- | ---
pin3 | pin4 | pin9 | pin10 | pin11 | pin12 | pin13 | pin14 | pin15 | pin16
b9  | b8  | b7  | b6  | b5  | b4  | b3  | b2  | b1  | b0
