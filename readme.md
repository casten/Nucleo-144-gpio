
# STM32 Nucleo-144 Boards GPIO Pins



## Background

I was working on a project that utilized a large number of GPIOs on a Nucleo-144 board.  Some pins were double-labled and not necessarily clear in the definitions in the headers.  Also some pins appeared to be not connected despite being labeled with pin named.

I made a mistake of picking the wrong board and then subsequently transcibing the wrong GPIOs for various PIN names.  This documentation is for NUCLEO-F767ZI which has Arduino pin definitions at:
Arduino15/packages/STMicroelectronics/hardware/stm32/2.11.0/variants/STM32F7xx/F765Z(G-I)T_F767(G-I)T_F777ZIT/variant_generic.h

I used a utility I wrote to help confirm the pins mappings to GPIO numbers.  You can find that here:  
[https://github.com/casten/gpio-tool](https://github.com/casten/gpio-tool)

## Top View of Board

For a top view of the board, refer to the following document:

[Nucleo-144-gpio.md](Nucleo-144-gpio.md)


## Back View of Board

I orginally transcribed from the back side as these have the silkscreen.  It's also a little easier to probe or wire there.
Here's the pinout from the backside.

[Nucleo-144-gpio-back.md](Nucleo-144-gpio.md)
