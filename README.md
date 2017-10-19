# SSD1306_HAL_EN_RU
SSD1306 HAL driver for STM32 with English and Russian fonts (I2C only)

How to use driver:
1. In your main.c file include "ssd1306.h".
2. In "/inc/ssd1306.h" file change inclusion of "stm32f0xx_hal.h" to hal driver like in your "main.c" file.
3. Init display with current library interface functions.
4. Set cursor where you want add text.
5. Write text string to buffer.
6. Update screen.

<p><b>---First upload v0.5---</b></p>

Only one 7*9px font with English and Russian (Windows1251) symbols.


