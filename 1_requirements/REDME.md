# Basic Requirements
The Following are the total Requirements to built Digital Clock Alarm,
* Hardware Components
* Software
* Embedded C Programming
# Requirements to built Digital Clock
The Following are the important requirements to builtDigital Clock,
* ATmega328
* 16x2 LCD Display
* Buzzer
* Push Button Switch
* Bread Board or Dote Board
* 16MHZ Crystal
* Capacitor-22PF
* Resistors-10k,330-Ohms,1.5k
* Jumper Wires
* 3.7V Battery
* DS3231 RTC
* Battery Charging Module-TP4056
# ATmega328 Micro-Controller
The ATmega328 is a single-chip microcontroller created by Atmel in the megaAVR family (later Microchip Technology acquired Atmel in 2016). It has a modified Harvard architecture 8-bit RISC processor core.

The Atmel 8-bit AVR RISC-based microcontroller combines 32 KB ISP flash memory with read-while-write capabilities, 1 KB EEPROM, 2 KB SRAM, 23 general-purpose I/O lines, 32 general-purpose working registers, 3 flexible timer/counters with compare modes, internal and external interrupts, serial programmable USART, a byte-oriented 2-wire serial interface, SPI serial port, 6-channel 10-bit A/D converter (8 channels in TQFP and QFN/MLF packages), programmable watchdog timer with internal oscillator, and 5 software-selectable power-saving modes. The device operates between 1.8 and 5.5 volts. The device achieves throughput approaching 1 MIPS/MHz.
[11:37 AM, 4/23/2022] ẞußhmä Reddy💮: ## Features Of ATmega328
|Parameter	|Value  |
|-----------|-------|
|CPU type	|8-bit AVR|
|Maximum CPU speed|	20 MHz|
|Performance	|20 MIPS at 20 MHz|
|Flash memory|	32 KB|
|SRAM	|2 KB|
|EEPROM|	1 KB|
|Package pin count|	28 or 32|
|Capacitive touch sensing channels|	16|
|Maximum I/O pins	|23|
|External interrupts|	2|
|USB interface|	No|
[11:38 AM, 4/23/2022] ẞußhmä Reddy💮: ## ATmega328 Micro-Controller Pin Description
The Atmega328 is a very popular microcontroller chip produced by Atmel. It is an 8-bit microcontroller that has 32K of flash memory, 1K of EEPROM, and 2K of internal SRAM.

The Atmega328 is one of the microcontroller chips that are used with the popular Arduino Duemilanove boards. The Arduino Duemilanove board comes with either 1 of 2 microcontroller chips, the Atmega168 or the Atmega328. Of these 2, the Atmega328 is the upgraded, more advanced chip. Unlike the Atmega168 which has 16K of flash program memory and 512 bytes of internal SRAM, the Atmega328 has 32K of flash program memory and 2K of Internal SRAM.

The Atmega328 has 28 pins.

It has 14 digital I/O pins, of which 6 can be used as PWM outputs and 6 analog input pins. These I/O pins account for 20 of the pins.
## ATmega328 Micro-Controller Pin Description
The Atmega328 is a very popular microcontroller chip produced by Atmel. It is an 8-bit microcontroller that has 32K of flash memory, 1K of EEPROM, and 2K of internal SRAM.

The Atmega328 is one of the microcontroller chips that are used with the popular Arduino Duemilanove boards. The Arduino Duemilanove board comes with either 1 of 2 microcontroller chips, the Atmega168 or the Atmega328. Of these 2, the Atmega328 is the upgraded, more advanced chip. Unlike the Atmega168 which has 16K of flash program memory and 512 bytes of internal SRAM, the Atmega328 has 32K of flash program memory and 2K of Internal SRAM.

The Atmega328 has 28 pins.

It has 14 digital I/O pins, of which 6 can be used as PWM outputs and 6 analog input pins. These I/O pins account for 20 of the pins.

![](http://www.learningaboutelectronics.com/images/Atmega328-pinout.png)

|Pin Number|	Description	|Function|
|----------|---------------|--------|
|1|	PC6	|Reset|
|2	|PD0	|Digital Pin (RX)|
|3	|PD1	|Digital Pin (TX)|
|4	|PD2	|Digital Pin|
|5	|PD3	|Digital Pin (PWM)|
|6	|PD4	|Digital Pin|
|7	|Vcc	|Positive Voltage (Power)|
|8 |	GND|	Ground|
|9	|XTAL 1|	Crystal Oscillator|
|10	|XTAL 2	|Crystal Oscillator|
|11	|PD5	|Digital Pin (PWM)|
|12	|PD6|	Digital Pin (PWM)|
|13	|PD7|	Digital Pin|
|14	|PB0|	Digital Pin|
|15	|PB1|	Digital Pin (PWM)|
|16	|PB2|	Digital Pin (PWM)|
|17	|PB3|	Digital Pin (PWM)|
|18	|PB4|	Digital Pin|
|19	|PB5|	Digital Pin|
|20	|AVCC	|Positive voltage for ADC (power)|
|21	|AREF|	Reference Voltage|
|22	|GND	|Ground|
|23	|PC0	|Analog Input|
|24	|PC1	|Analog Input|
|25	|PC2	|Analog Input|
|26	|PC3	|Analog Input|
|27	|PC4	|Analog Input|
|28	|PC5	|Analog Input|
# Detail Requirements
## High Level Requirements

|  ID  |  Description  |
| ------  | ------  |
|  HLR1  |  Knowledge of ATmega328 | 
|  HLR2  |  Writing the code  |
|  HLR3  |  Making the Circuit  |

## Low Level Requirements

|  ID  |  Description  |
|  ------  |  ------  |
|  LLR1  |  Knowledge of Components   |
|  LLR2  |  Adding necessary library files for ATmega328 AVR-gcc Compiler  |
|  LLR3  |  Implimenting circuit in Simu Ide  |
