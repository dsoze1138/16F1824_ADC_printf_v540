# PIC16F1824 ADC and printf demo
--------------------------------

This is a demo project in answer to a question on Stack Overflow.

See: https://stackoverflow.com/questions/63957642/float-to-string-using-pic16f1824

This project was created with the MPLABX v5.40 Code Configurator.

It samples the voltage present on the AN2 input pin. Using 32-bit integer math 
the value is converted from ADC binary units to voltage units based on the VREF 
voltage use for the Analog to Digital Conversion(ADC) function block in the 
PIC16F1824.

The printf() statement is used to display this value using the UART serial 
function block at a 9600 baud rate.

This demo code does run using the MPLABX v5.40 simulator and simulator 
stimulus file (16F1824_ADC_printf_v540.sbs) to set the voltage on the AN2 pin.