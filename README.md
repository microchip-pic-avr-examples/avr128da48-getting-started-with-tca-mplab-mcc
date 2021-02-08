[![MCHP](images/microchip.png)](https://www.microchip.com)

# Getting Started with Timer/Counter Type A (TCA) Examples (MPLAB® X)

This repository contains examples of MPLAB® Code Configurator (MCC) generated source code for Timer/Counter Type A (TCA) as described in [TB3217 - Getting Started with Timer/Counter Type A (TCA)](https://ww1.microchip.com/downloads/en/Appnotes/TB3217-Getting-Started-with-TCA-DS90003217.pdf) document from Microchip. The repository contains three MPLAB® X Integrated Development Environment (IDE) projects inside:

* [<strong>Generating a Dual-Slope PWM Signal:</strong>](Generating_a_Dual-slope_PWM_Signal) This use case shows how to generate a dual slope 16-bit PWM signal with 1 kHz frequency and 50% duty cycle on a GPIO pin (for more details, see [<strong>Generating a Dual-Slope PWM Signal</strong>](Generating_a_Dual-slope_PWM_Signal))
* [<strong>Generating Two PWM Signals in Split Mode:</strong>](Generating_Two_PWM_Signals_in_Split_Mode) This use case shows how to initialize the timer in Split mode to generate two single-slope 8-bit PWM signals on two GPIO pins, with independent duty cycle and frequency (for more details, see [<strong>Generating Two PWM Signals in Split Mode</strong>](Generating_Two_PWM_Signals_in_Split_Mode))
* [<strong>Using Periodic Interrupt Mode:</strong>](Using_Periodic_Interrupt_Mode) This use case shows how to initialize the timer in Single mode to work as a counter. The counter overflows every 250 ms and triggers an interrupt, which toggles a pin (for more details, see [<strong>Using Periodic Interrupt Mode</strong>](Using_Periodic_Interrupt_Mode))

## Related Documentation
More details and code examples on the AVR128DA48 can be found at the following links:
- [TB3217 - Getting Started with Timer/Counter Type A (TCA)](https://ww1.microchip.com/downloads/en/Appnotes/TB3217-Getting-Started-with-TCA-DS90003217.pdf)
- [AVR128DA48 Product Page](https://www.microchip.com/wwwproducts/en/AVR128DA48)
- [AVR128DA48 Code Examples on GitHub](https://github.com/microchip-pic-avr-examples?q=avr128da48)
- [AVR128DA48 Project Examples in START](https://start.atmel.com/#examples/AVR128DA48CuriosityNano)


## Software Used
- MPLAB® X Integrated Development Environment (IDE) 5.40 or newer [(microchip.com/mplab/mplab-x-ide)](http://www.microchip.com/mplab/mplab-x-ide)
- MPLAB® XC8 2.30 or a newer compiler [(microchip.com/mplab/compilers)](http://www.microchip.com/mplab/compilers)
- MPLAB® Code Configurator (MCC) 4.0.1 or newer [(microchip.com/mplab/mplab-code-configurator)](https://www.microchip.com/mplab/mplab-code-configurator)
- MPLAB® Code Configurator (MCC) Device Libraries 8-bit AVR MCUs 2.5.0 or newer [(microchip.com/mplab/mplab-code-configurator)](https://www.microchip.com/mplab/mplab-code-configurator)
- AVR-Dx 1.4.75 or a newer Device Pack


## Hardware Used
- AVR128DA48 Curiosity Nano [(DM164151)](https://www.microchip.com/Developmenttools/ProductDetails/DM164151)
