# ya_micropython_teenys_fork
experimenting with micropython for teensy
Using base code from  dhylands/micropython i am try to get familiar with c-code and python for the teensy.
So far i have been able to get the adc and DAC working by calls to the analog.c file located in the core which 
was already complided in the base code.
example:
from pyb import DAC
from pyb import ADC
adc = ADC(1)
dac = DAC(1)
dac.write(1023)
a = adc.read(0
print (a)


