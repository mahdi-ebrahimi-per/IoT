> note : the main code is in `./codeVision` directory, you can unzip and use them. <br>
> the `./code_preview.c` is just preview and doesn't work currectly. <br>

<br>

## microcontroller 
- model : AVR-ATMEGA-32A
- Adjusted clock : 12 MHz

<br>
<br>


## GLCD
- Display type : KS0108 128x64 CS1,CS2

<br>
<br>

## Project
Draw 4 line in 4 side of GLCD as border

<br>
<br>

## Pinouts


<img src="https://github.s3.ir-thr-at1.arvanstorage.com/GLCD-pinout.png" alt="ALCD pinout" width="600"/>
<br>
<img src="https://github.s3.ir-thr-at1.arvanstorage.com/GLCD-pinout-exp.png" width="600"/>


<br>
<br>


## GLCD functions

you can see GLCD functions in `./glcd functions.txt`

<br>
<br>

## Bread Board Circuit
you can see fritzing file in `./BreadBoard-fritzing.fzz`
<br>
<br>
<img src="https://github.s3.ir-thr-at1.arvanstorage.com/GLCD-circuit.png" alt="circuit" width="800"/>
<br>
<br>
we connect `GLCD Data Ports` to Port-C and connect `GLCD Control Ports` to Port-D, but you can change this (remember you must to change it too in CodeWizard part)


<br>
<br>

## Pins, Fuse bits & GLCD connect
<img src="https://github.s3.ir-thr-at1.arvanstorage.com/GLCD-ports-1.png" alt="GLCD ports" width="600"/>
<br>
<img src="https://github.s3.ir-thr-at1.arvanstorage.com/GLCD-ports-2.png" alt="GLCD ports" width="600"/>
Experimentally is better to pullup `P` the input GLCD ports, but it's not mandatory.
<br>
<br>
<br>
<img src="https://github.s3.ir-thr-at1.arvanstorage.com/GLCD-ports-3.png" alt="GLCD ports" width="600"/>
<br>
<img src="https://github.s3.ir-thr-at1.arvanstorage.com/GLCD-ports-4.png" alt="ALCD fuse bit"/>
<br>
<img src="https://github.s3.ir-thr-at1.arvanstorage.com/GLCD-ports-5.png" alt="ALCD fuse bit"/>
