## STM32F042 Board

![PCB Rendering](rendering.png)

Dev board for the
[STM32F042](https://www.st.com/resource/en/datasheet/stm32f042c4.pdf).

### Programming

I'm using the ST-Link on an ST Discovery board to program this.

These ST Header CN2 Pins should be connected to the corresponding pins on this
dev board:

1. Don't connect
2. CLK
3. GND
4. DIO
5. NRST

Leave pin 1 (target 3V3) unconnected. It seems to do no harm, but it won't work
if connected.

