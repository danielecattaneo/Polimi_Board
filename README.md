# Polimi_Board
Design of new board for **Politecnico di Milano** Univeristy. \
This project is for the Embedded Systems course.
## Description
The board is based on *STM32* chip - **[STM32F205RCT6](https://www.st.com/resource/en/datasheet/stm32f205rb.pdf)** as a main core.

# Board Design specifications
- 1x [specific main core chip](https://estore.st.com/en/stm32f205rct6-cpn.html)
- 1x micro-USB B Port, directly connencted to the main chip.
- 1x micro-USB B Port, for serial progeamming chip **FT2232**
- 1x micro-SD Port
- 1x Ethernet Port, with magnetic transformer included, wired to **LAN8742** chip
- 1x reset button
- 6x General buttons, 4 of them placed as a joystick cross, the others beside
- 1x power LED
- 1x LED linked to a GPIO Port
- 1x OLED SCREEN I2C, [like](https://www.amazon.it/AZDelivery-Display-retroilluminato-Raspberry-gratuito/dp/B078J78R45?ref_=ast_sto_dp&th=1), or [like](https://www.ebay.it/itm/204428760352?itmmeta=01HQXT2FC1579AP9QA0BS3KWXZ&hash=item2f98e75520:g:HqMAAOSw8oZhO3MO)
- 1x External Flash SPI chip

## Usefull Links
- [Big Board reference with Ram](https://github.com/HEAPLab/marco-ram-board/tree/master)
- [Thermal camera project](https://github.com/fedetft/thermal_camera)
