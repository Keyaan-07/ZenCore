# Zencore F4
Zencore F4 is a low-cost, Pico sized STM32F411 Development board along with an SD card reader for SDMMC development. The footprint is breadboard compatible and it features the W25Q128JVS 128Mbit Flash chip for non-volatile storage. Unlike traditional devboards, this features a compact form factor. The pins are labelled on the bottom side of the PCB.  
I want to use the stm32f411 mcu for a bigger project and thus i will be experimenting with this one(hence the SD card interface). Just plug in the USB-C to your PC and upload the code via STM32cubeIDE to get started.  
To build this, clone/download this repository, and in the /hardware/production folder, use the files and the bom to order the parts yourself and assemble it by hand!


See the board on [KiCanvas](https://kicanvas.org/?github=https://github.com/Keyaan-07/ZenCore/tree/main/hardware)
![magazine page](/media/Zencore_zine.png)
![3d-top](/media/3d-top.png)
![3d-side](/media/3d-side.png)
![3d-bottom](/media/3d-bottom.png)
![pcb-top](/media/pcb-top.png)
![schematic](/media/schematic.png)


#BOM
|Designator              |Function         |Value                      |Footprint                                      |Quantity|Price        |Amount|Order|Link                                              |
|------------------------|-----------------|---------------------------|-----------------------------------------------|--------|-------------|------|-----|--------------------------------------------------|
|PCB                     |PCB              |21x51                      |2 layer board                                  |5       |0.42         |2.1   |Yes  |https://jlcpcb.com                                |
|PCB Stencil             |Stencil          |40x55                      |stencil                                        |1       |3.05         |3.05  |Yes  |https://jlcpcb.com                                |
|C1, C10, C12, C2, C3, C4|Capacitor        |100n                       |402                                            |12      |0.0075       |0.09  |No   |https://www.lcsc.com/product-detail/C426067.html  |
|C11                     |Capacitor        |10u                        |603                                            |2       |0.02         |0.04  |No   |https://www.lcsc.com/product-detail/C7393892.html |
|C5                      |Capacitor        |1u                         |402                                            |20      |0.03         |0.6   |yes  |https://www.lcsc.com/product-detail/C1518208.html |
|C6                      |Capacitor        |4.7u                       |402                                            |10      |0.04         |0.4   |Yes  |https://www.lcsc.com/product-detail/C426094.html  |
|C7, C8                  |Capacitor        |22p                        |402                                            |4       |0.03         |0.12  |No   |https://www.lcsc.com/product-detail/C882567.html  |
|C9                      |Capacitor        |22u                        |603                                            |10      |0.014        |0.14  |Yes  |https://www.lcsc.com/product-detail/C86295.html   |
|D1, D2                  |LED              |LED                        |402                                            |50      |0.01         |0.5   |Yes  |https://www.lcsc.com/product-detail/C7496805.html |
|J1                      |SD card connector|Micro_SD_Card              |microSD_HC_Molex_104031-0811                   |2       |0.63         |1.26  |Yes  |https://www.lcsc.com/product-detail/C585350.html  |
|J2                      |USB-C Receptacle |USB_C_Receptacle_USB2.0_16P|USB_C_Receptacle_XKB_U262-16XN-4BVC11          |10      |0.066        |0.66  |Yes  |https://www.lcsc.com/product-detail/C393939.html  |
|J3, J4                  |header           |Conn_01x20_Pin             |PinHeader_1x20_P2.54mm_Vertical                |2       |DNP          |DNP   |DNP  |DNP                                               |
|L1                      |Inductor         |2.2u                       |805                                            |5       |0.1          |0.5   |Yes  |https://www.lcsc.com/product-detail/C48945029.html|
|R1, R2, R3, R7, R9      |Resistors        |5.1k                       |402                                            |10      |0.005        |0.05  |No   |https://www.lcsc.com/product-detail/C278598.html  |
|R10, R4                 |Resistors        |100k                       |402                                            |4       |0.02         |0.08  |No   |https://www.lcsc.com/product-detail/C313329.html  |
|R5, R6                  |Resistors        |100R                       |402                                            |4       |0.037        |0.148 |No   |https://www.lcsc.com/product-detail/C427204.html  |
|SW1, SW2                |Switch           |SW_Push                    |SW-SMD_L3.9-W3.0-P4.45                         |10      |0.056        |0.56  |Yes  |https://www.lcsc.com/product-detail/C720477.html  |
|U1                      |flash chip       |W25Q128JVS                 |SOIC-8_5.3x5.3mm_P1.27mm                       |2       |DNP          |DNP   |DNP  |DNP                                               |
|U2                      |MCU              |STM32F411CEUx              |QFN-48-1EP_7x7mm_P0.5mm_EP5.6x5.6mm            |2       |3.87         |7.74  |Yes  |https://www.lcsc.com/product-detail/C60420.html   |
|U3                      |Buck Convertor   |TPS62162DSG                |WSON-8-1EP_2x2mm_P0.5mm_EP0.9x1.6mm_ThermalVias|2       |0.86         |1.72  |Yes  |https://www.lcsc.com/product-detail/C40256.html   |
|Y1                      |Crystal          |25MHz                      |Crystal_SMD_3225-4Pin_3.2x2.5mm                |2       |             |0     |No   |https://www.lcsc.com/product-detail/C521601.html  |
|                        |                 |                           |                                               |        |Shipping     |3.9   |     |                                                  |
|                        |                 |                           |                                               |        |Shipping(PCB)|11.13 |     |                                                  |
|                        |                 |                           |                                               |        |Total        |34.788|     |                                                  |


