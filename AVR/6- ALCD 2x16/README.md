> note : the main code is in `codeVision` directory, you can unzip and use them. <br>
> the `code_preview.c` is just preview and doesn't work currectly. <br>

### microcontroller 
- model : AVR-ATMEGA-32A
- core clock : 12 MHz

### Project
input 8-bit dip-switch for binary number input to PORT-C.
<br>
transfer binary to decimal and show it in the ALCD screen.


<br>
<br>

<img src="https://github.s3.ir-thr-at1.arvanstorage.com/alcd.jpg" alt="ALCD pinout" width="600"/>

we see ALCD function in CodeVision :  

## lcd_gotoxy (int ,int );

move cursor to x, y of 2x16 and start putting text from there.

<br>

## lcd_clear( );

clear all text on the lcd.

<br>

## lcd_puts( char*str );

put string on the screen, that read (save `char*str`) from/on RAM.
<br>
here we input Variable in this function.

<br>

## lcd_putsf( char*str );

put string on the screen that read (save `char*str`) from/on FLASH.
<br>
here we input string in this function.


<br>
<br>

# Bread Board Circuit
<img src="https://github.s3.ir-thr-at1.arvanstorage.com/ALCD-circuit.png" alt="circuit" width="800"/>

<br>
<br>

# Pins, Fuse bits & ALCD connect
<img src="https://github.s3.ir-thr-at1.arvanstorage.com/ALCD_Ports.png" alt="ALCD ports" width="600"/>
<br>
<img src="https://github.s3.ir-thr-at1.arvanstorage.com/ALCD_connect.png" alt="ALCD connect" width="600"/>
<br>
<img src="https://github.s3.ir-thr-at1.arvanstorage.com/ALCD_fusebit.png" alt="ALCD fuse bit"/>
<br>
<img src="https://github.s3.ir-thr-at1.arvanstorage.com/GLCD-chksl.png" alt="ALCD fuse bit"/>



