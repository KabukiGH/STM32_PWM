# STM32_PWM
DMA with ADC using Registers in STM32
Project has to deliver source code for microcontroller STM32 F411CE, which include the configuration and the use:
-DMA
-ADC
-Timers (PWM)

The goal of the project was to get familiar with above microcontroller periphery, and the task was to controll and set servo position according to reading analog potentiometer value. 

During the tests it was shown that the PWM signal fill values given by the servo manufacturer, do not cover in reality for the extreme positions (0 and 180 degrees), the solution turned out to be a proportional increase and decrease of the PWM signal. So that the servo achieves the full and declared range of motion
