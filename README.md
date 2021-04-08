A development board for Atmega328p, with basics like 

8x LED on PB0-7
LDR / Potmeter
Servo header / servo power selector 
Two pushbuttons, one at each INT0/1
I2C header 
Serial header 

Several jumpers, to make optimal use of pins.

Selections via jumpers:
1) Use either crystal or LEDs on PB6/7
2) Use either LDR or Potmeter at PC0
3) Use either Servo or LED at PB1 / T1 16-bit timer OC1A
4) Use either VCC voltage for servo, or seperately supplied voltage

PINs available for
1) I2C
2) Serial GND/TX/RX
3) INT0/INT1

Photo shows an earlier PCB with switched labels. Current gerbers are correct and have been printed correctly at JLCPCB.

![](Final.jpg)
