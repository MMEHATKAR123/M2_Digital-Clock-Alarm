# Digital Clock Alarm 
# Introduction
A digital clock is a type of clock that displays the time digitally that is  in numerals or other symbols, as opposed to an analogue clock. Digital clocks are often associated with electronic drives, but the "digital" description refers only to the display, not to the drive mechanism.

They are designed to make a signal / alarm at a specific time. The use of digital alarm clocks has increased over years with development in electronics. The advantage of digital alarm clocks over analogue alarm clocks is that they require less power, the time can be set or reset easily and displays the time in digit.

# Objective of Project
The objective of this project is to design and build a digital clock.The clock is designed to show the hour, minute, second, am and pm functionusing LCD display panel. The clock design must have other alternative devices.An alarm circuit is also connected to facilitate the alarm command which will be produced by an alarm buzzer.
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
## Features Of ATmega328
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
## Block Diagram
The block diagram of ATmega328 is given by,

![](https://microcontrollerslab.com/wp-content/uploads/2019/12/ATMEGA328P-Block-Diagram.jpg)
## Applications of ATmega328
The following are the applications of atmega328 microcontroller,
* A complete package including ATmega 328 and Arduino can be used in several different real-life applications.
* It can be used in Embedded Systems Projects.
* It can also be used in robotics.
* Quad-copter and even small aero-plane can also be designed through it.
* Power monitoring and management systems can also be prepared using this device.
* I have designed this Home Security System using Arduino UNO, you should have a look at it.
# Software
The software manages various hardware devices and systems. The basic idea behind embedded systems software is to control the functioning of a set of hardware devices without compromising on the purpose or the efficiency. Embedded systems software can be compared to the operating systems in computers.
## SimulIDE
SimulIDE is a simple real time electronic circuit simulator, intended for hobbyist or students to learn and experiment with simple electronic circuits and microcontrollers, supporting PIC, AVR and Arduino.This is not an accurate simulator for circuit analysis, it aims to be fast, simple and easy to use, this means simple and not very accurate electronic models and limited features.

You can create, simulate and interact with your circuits within minutes, just drag components from the list, drop into the circuit, connect them and push power button to see how it works.

![](https://1.bp.blogspot.com/-g0PfHcs2isw/XtlQcrj8DVI/AAAAAAAABRo/slmqFRdR6AA6sNNF59r1-NTUvEodcPH8gCLcBGAsYHQ/s320/circuit.gif)

SimulIDE also features a code Editor and Debugger for GcBasic, Arduino, PIC asm and AVR asm. It is still in it's firsts stages of development, with basic functionalities, but it is possible to write, compile and basic debugging with breakpoints, watch registers and global variables.
## AVR Cross Compiler
AVR-GCC is a compiler that takes C language high level code and creates a binary source which can be uploaded into an AVR micro controller. Thus AVR-GCC might be regarded as a 'C' cross compiler for producing AVR code. AVR-libc are 'C' run-time libraries, header files, and documentation primarily for the AVR target and are used in conjunction with AVR-GCC . Please note that AVR-libc and AVRLIB are different sets of libraries but both work with the AVR-GCC compiler.

Once code in 'C' is written for a particular project AVR-GCC will turn C code into assembly language files. AVR-libc includes all the header files that contain the addresses of port and register names, the floating point library, AVR-specific macros, and AVR start-up code. It also provides a lot of documentation, both on the library items itself as well as on a number of general items on the entire tool chain, including a FAQ.

Individual assembler files are then converted into object files. Object files are files of code that AVR chips could run. The linker AVR-ld will take all these assembler files, and cross-reference functions names to create one single object file. The linker will also take modules from the 'C' library and make them into a single object. Normally this linked object is in ELF format and furthermore AVR-objcopy is used to generate a HEX format file.

To install AVR-GCC as well as all AVR-Tools like avr-libc, avr-gcc-c++, avr-binutils, avr-gdb, avr-libc-docs on Fedora 7 and above, as root, just issue the 'yum' command with something like:

      [host] yum install avr-*  
      
Other Linux distributions use the 'apt-get' command in a similar way. For OS-X, CCRMA's PID Wiki has instructions for Setting up your Computer for AVR Development. Fink on OS-X might include AVR-GCC as well AVR-Tools. 
## Visual Studio Code
Visual Studio Code, also commonly referred to as VS Code, is a source-code editor made by Microsoft for Windows, Linux and macOS. Features include support for debugging, syntax highlighting, intelligent code completion, snippets, code refactoring, and embedded Git. Users can change the theme, keyboard shortcuts, preferences, and install extensions that add additional functionality.

Visual Studio Code is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux.

![](https://user-images.githubusercontent.com/4492249/87854967-a51f2780-c915-11ea-894d-0450d9253343.png)

## Embedded C Language
Embedded C is a set of language extensions for the C programming language by the C Standards Committee to address commonality issues that exist between C extensions for different embedded systems.

Embedded C programming typically requires nonstandard extensions to the C language in order to support enhanced microprocessor features such as fixed-point arithmetic, multiple distinct memory banks, and basic I/O operations. The C Standards Committee produced a Technical Report, most recently revised in 2008 and reviewed in 2013,providing a common standard for all implementations to adhere to. It includes a number of features not available in normal C, such as fixed-point arithmetic, named address spaces and basic I/O hardware addressing. Embedded C uses most of the syntax and semantics of standard C, e.g., main() function, variable definition, datatype declaration, conditional statements (if, switch case), loops (while, for), functions, arrays and strings, structures and union, bit operations, macros, etc.
# Desired Features of software
* Reader Master ??? Should allow editing of various access points and their interface details viz. IP address, Unit ID, Com Port.
* Employee Master - Allows editing of employee details, like name, employee
number, shift, access zones.
* Reader Configuration - Allows modification of reader parameters, like operating mode, door open time, welcome string, Alarm settings, Timeouts, etc. These parameters are also stored in the local database.
* Card Personaliser / Finger Encoding (option): Allows Mifare card/ Finger print encoding based on the employee master information. Needs externally connected personaliser.
* Offline Data Gathering ??? Periodically polls all the connected readers for swipe data and displays with user photograph if available. Data is available in near real-time(within 30 seconds).
* Headcount ??? Zonewise presence of employees is available. Alternately employee can be tracked within a zone.
* Clock Data Editing - Allows editing of the time data (by administrators with time data edit permission).
* Database : MYSQL
* Export Function - Export function can be used to export data to a CSV file.
* Time Synchronization - Time can be synchronized of all the connected readers on a
periodic basis.
* Large Data -Upto 10Gb data can be stored in the current tables. Older data is moved
to archives. Instantaneous Reports are available on the current table data.
* Easy of Operation: User can group different readers and employees. Different actions can be applied to selected group of readers or employees.
  * Installation & commissioning -
Installation & commissioning will be completely done by supplier and All
installation related works like electrification,casing-caping & routing of cables as per requirements, carpentry & civil work has been done by supplier with no any extra cost supplier must do arrangement of required material & items for completion of this work.
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

## Further Development:
* We can extend this project features by adding humidity, Air Quality display and even upgrade this into automatic light system and Visitor Counter System.
* For displaying Humidity we can use Hygrometer 
* For displaying Air Quality we can use Optical sensors, Metal Oxide Sesnor(To measure Nitrogen, Oxygen and Carbondioxide),Photo Ionization Sensor.
* For Visitor Counter we can use Ultra Sonic Sensor.
* For Automatic Light Sytem we can PIR Sensor. 

## SWOT Analysis:
* Strenghts: Count down alarm in digital clock.

* Weakness: If the user enters wrong password buzzer wont go off, there is no reset option. 

* Oppurtunities: Can be extended for displaying Humidity, Air Quality etc.

* Threats: No major threats.

## 4W's & 1H:
* Who: Can be used by every person
* What: For calculating countdown for Digital Alarm Clock.
* When: Can be utilized when a person needs an alarm.
* Where: House, Offices
* How: By using Atmega328 and Other Components.
