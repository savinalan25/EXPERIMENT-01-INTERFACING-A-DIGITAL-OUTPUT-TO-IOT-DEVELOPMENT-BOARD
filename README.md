# EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD
EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD
EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD
DATE:

NAME:

ROLL NO:

DEPARTMENT:

Aim
To Interface a Digital output (LED) to ARM IOT development board and write a program to blink an LED.

Components required
STM32 CUBE IDE
ARM IOT development board
STM programmer tool
Theory
The ARM (Advanced RISC Machine) architecture is widely used in microcontrollers and processors due to its efficiency, low power consumption, and high performance. ARM processors follow the Reduced Instruction Set Computing (RISC) design, making them ideal for embedded systems, mobile devices, and IoT applications. Many well-known semiconductor companies, including STMicroelectronics, use ARM-based architectures to develop powerful and energy-efficient microcontrollers.

One such microcontroller is the STM32WLE5JC, which is part of the STM32 family and is based on the ARM Cortex-M4 core. It is specifically designed for LoRaWAN® and other sub-GHz wireless communication applications, making it ideal for IoT and LPWAN (Low Power Wide Area Network) solutions. This microcontroller integrates a LoRa® transceiver, eliminating the need for an external radio module and reducing both cost and power consumption. With a maximum clock speed of 48 MHz, 256 KB of Flash memory, and 64 KB of RAM, it provides enough computing power for real-time data processing and wireless communication.

The STM32WLE5JC is known for its ultra-low power consumption, making it perfect for battery-operated IoT devices such as smart agriculture sensors, environmental monitoring systems, industrial automation, and asset tracking. It supports multiple communication interfaces, including I2C, SPI, and UART, allowing seamless integration with various sensors and peripherals. Additionally, it features built-in security capabilities such as AES 256-bit encryption and a True Random Number Generator (TRNG) for secure data transmission.

With its power-efficient design, built-in LoRaWAN support, and flexible communication options, the STM32WLE5JC is an excellent choice for developers looking to build long-range, low-power IoT applications. It is fully compatible with STM32CubeIDE and LoRaWAN middleware, making development and deployment easier for engineers and learners alike.

Procedure
Click on STM 32 CUBE IDE, the following screen will appear
image

Click on FILE, click on new stm 32 project
image image

Select the target to be programmed as shown below and click on next
Screenshot 2025-03-11 134231

Select the program name
image

Corresponding ioc file will be generated automatically
Screenshot 2025-03-11 134528

Select the appropriate pins as GPIO, in or out, USART or required options and configure
Screenshot 2025-03-11 134617

Screenshot 2025-03-11 134642

Click on Ctrl+S, automatically C program will be generated
Screenshot 2025-03-11 134709

Edit the program and as per required
image

Use project and build all
image

Once the project is bulild
image

connect the iot board to power supply and usb

After connecting open the STM cube programmer

Screenshot 2025-03-11 135208

Connect the STM board through the COM port, then upload the corresponding project ELF file/Hex file or Bin file in Erasing & Programming Window,while ensuring the board is in flash mode, and click on 'Start Program'.

image

After the file download is complete, switch your board to run mode and press the reset button to see the output

STM 32 CUBE PROGRAM
// Your STM 32 CUBE Program code here
OUTPUT
Result
Interfacing a digital output with ARM microcontroller based IOT development is executed and the results are verified.
