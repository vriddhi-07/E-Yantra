AIM
In this experiment, we will interface ADC with the micro-controller.  
The aim of this experiment is to get us familiar with ADC present on Firebird V robot.

ATmega2560 features a 10-bit successive approximation ADC.  
This built-in ADC is connected to an 16 channel Analog Multiplexer which allows 16 single ended voltage inputs constructed from the pins of Port K and Port F of ATmega2560.

In this experiment, we will interface the White Line and IR Proximity sensors already connected on Firebird V robot.  
The aim of this experiment is to get us familiar with the configuring and interfacing of these sensors and using the built-in ADC of ATmega2560.

The task is to get the 10-bit ADC result from the 2nd Sharp sensor in Single Conversion Mode using the ADC Conversion Interrupt.  
Display the ADC data on LCD and send the same to UART Serial Terminal.

The program is provided in a project folder.  
But, the program contains few incomplete functions which have to be completed as per the instructions present in the comments.  
The functions necessary for initialization of LCD and UART are already defined and called in the main() function.
