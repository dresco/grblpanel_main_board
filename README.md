# grblPANEL reference board

KiCad implementation of a grblPANEL control board, with the following features;
- up to 88 input keys
- up to 4 quadrature encoders
- display output (reference design using a 3.5" ILI9488 panel)
- Modbus and CAN bus (WIP) connectivity to grblHAL controller
- SWD connector (2x5 1.27mm) for programming and debugging
- USB C interface for programming and configuration (WIP)
- ESD protection on all user connections
- 5-12V DC power input - with reverse polarity, undervoltage, overvoltage, and overcurrent protection

The control board uses the following high level components;
- STM32G0 MCU running at 64MHz
- TI SN65HVD230 CAN transceiver
- TI THVD1406 Modbus transceiver
- Analog Devices ADP5589 I/O expander
- Analog Devices MAX17612A power protection IC

![back](https://github.com/dresco/grblpanel_main_board/blob/master/images/main_board_back.png)
![front](https://github.com/dresco/grblpanel_main_board/blob/master/images/main_board_front.png)

