.. _beagleconnect_freedom:

BeagleBoard.org BeagleConnect Freedom
#################

Overview
********

BeagleBoard.org BeagleConnect Freedom is a wireless
Internet of Things board based on the SimpleLink multi-Standard CC1352P wireless MCU.


.. figure:: img/beagleconnect_freedom.png
   :width: 400px
   :align: center
   :alt: BeagleBoard.org BeagleConnect Freedom

   BeagleBoard.org BeagleConnect Freedom

Hardware
********
BeagleBoard.org BeagleConnect Freedom board features the CC1352P wireless microcontroller.
The BeagleConnect Freedom is the first available BeagleConnect solution consisting
of a board and a case which ships programmed and ready to be used.

BeagleConnect Freedom board runs the Zephyr RTOS and has mikroBUS ports along 
with BLE and Sub-GHz radios on it.

The CC1352P wireless MCU has a 48 MHz Arm Cortex-M4F SoC and a Bluetooth Low Energy and IEEE 802.15.4.


Supported Features
==================

The CC1352P LaunchPad board configuration supports the following hardware
features:

+-----------+------------+----------------------+
| Interface | Controller | Driver/Component     |
+===========+============+======================+
| GPIO      | on-chip    | gpio                 |
+-----------+------------+----------------------+
| PINMUX    | on-chip    | pinmux               |
+-----------+------------+----------------------+
| UART      | on-chip    | serial               |
+-----------+------------+----------------------+
| I2C       | on-chip    | i2c                  |
+-----------+------------+----------------------+
| SPI       | on-chip    | spi                  |
+-----------+------------+----------------------+

Other hardware features are not supported by the Zephyr kernel.

Connections and IOs
===================

+-------+-----------+---------------------+
| Pin   | Function  | Usage               |
+=======+===========+=====================+
| DIO5  | RST_MB2   | I2C SDA             |
+-------+-----------+---------------------+
| DIO6  | RST_MB1   | Red LED             |
+-------+-----------+---------------------+
| DIO7  | INT_SENSOR| Green LED           |
+-------+-----------+---------------------+
| DIO8  | FLASH_CS  | SPI MISO            |
+-------+-----------+---------------------+
| DIO9  | MOSI      | SPI MOSI            |
+-------+-----------+---------------------+
| DIO10 | SCK       | SPI CLK             |
+-------+-----------+---------------------+
| DIO11 | MISO      | SPI CS              |
+-------+-----------+---------------------+
| DIO12 | COM1      | UART RXD            |
+-------+-----------+---------------------+
| DIO13 | COM2      | UART TXD            |
+-------+-----------+---------------------+
| DIO14 | 900M      | Button 2            |
+-------+-----------+---------------------+
| DIO15 | USER_BOOT | Button 1            |
+-------+-----------+---------------------+
| DIO16 |CC1352_TDO | JTAG TDO            |
+-------+-----------+---------------------+
| DIO17 |CC1352_TDI | JTAG TDI            |
+-------+-----------+---------------------+
| DIO18 | 2.4G      | UART RTS / JTAG SWO |
+-------+-----------+---------------------+
| DIO19 | PWM_MB2   | UART CTS            |
+-------+-----------+---------------------+
| DIO20 | INT_MB2   | Flash CS            |
+-------+-----------+---------------------+
| DIO21 |CC1352_TX_MB2_RX|                |
+-------+-----------+---------------------+
| DIO22 | CC1352_RX_MB2_TX|               |
+-------+-----------+---------------------+
| DIO23 |AN_MB1     | A0                  |
+-------+-----------+---------------------+
| DIO24 | AN_MB2    | A1                  |
+-------+-----------+---------------------+
| DIO25 |SCL        | A0                  |
+-------+-----------+---------------------+
| DIO26 | SDA       | A1                  |
+-------+-----------+---------------------+
| DIO27 | CS_MB2    | A4                  |
+-------+-----------+---------------------+
| DIO28 | CS_MB1    | A5                  |
+-------+-----------+---------------------+
| DIO29 | INT_MB1   | A6                  |
+-------+-----------+---------------------+
| DIO30 | PWM_MB1   | A7                  |
+-------+-----------+---------------------+

References
*********


BeagleBoard.org BeagleConnect Freedom reference repository:
  https://beagleconnect.org
