# stm32-pwm-generator
Generates PWM at 10% duty cycle with 8-bit timer. Blinking LED included.

## Hardware
- Board: STM32 Nucleo-F401RE

## CubeMX
- Timer: TIM2 Channel 1
- Pulse: 25
- Counter Period: 255
- Duty Cycle: 10%

  ## Images
![description](https://github.com/noaheruiz/stm32-pwm-generator/blob/593a846615417c22565ef152013a5126560eb244/IMG_2493.JPEG)
Oscilloscope shows 10% duty cycle and average voltage around 380mV. Frequency is 333kHz since my prescaler is 0, counter period, or ARR, is 255, and my clock speed is 84MHz.
