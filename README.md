# Samsung-RISC-V-Workshop
**The RISC-V Workshop, certified by Samsung and VLSI Design, offers an immersive hands-on experience in RISC-V architecture, under the expert guidance of Kunal Ghosh. The workshop leverages the VSD Squadron Mini Board, a RISC-V-based development platform, designed to provide participants with real-world exposure to the design, implementation, and optimization of RISC-V processors.**

Basic Details

<b>Name:</b> Chidananda R

<b>College:</b> Global Academy Of Technology

<b>Email ID:</b> chidanandar9686@gmail.com

<b>GitHub Profile:</b> Chidananda-R

<b>LinkedIN Profile:</b> Chidananda R


<details>
<summary><h3> STEPS TO SETUP LAB</h3> </summary>

![Virtual Box for VSD Workshop](https://github.com/user-attachments/assets/ea63fc96-788b-4694-9d87-ad76b39f49cc)
![Step1](https://github.com/user-attachments/assets/840f4d2c-aff1-4262-a966-e83a91c9811b)
![Step2](https://github.com/user-attachments/assets/0f0dd290-9230-4e8c-ab70-0a4a3a0933a2)
![Step3](https://github.com/user-attachments/assets/fee0f92b-42b5-4207-afef-dedb8fba5b75)
![Step4](https://github.com/user-attachments/assets/17c789fb-bacb-4ed5-a795-7647e95f1c46)
![Step5](https://github.com/user-attachments/assets/576f5795-2ace-4e95-93b0-f7857b2a93b8)
![Step6](https://github.com/user-attachments/assets/0dff82ec-b1b9-45f0-b0e9-b5143a01c3d1)
![Step7](https://github.com/user-attachments/assets/a8d55604-2579-4c4f-a970-2d3ae5e329cb)
![Step8](https://github.com/user-attachments/assets/1bc2459f-e020-4b50-a305-7c30588c1cf0)

**VSD SQUADRON BOARD**

![VSD Squadron Mini RISC-V development board](https://github.com/user-attachments/assets/9519c12c-8542-4401-8c5d-ef7841ddf0fe)
![VSD Squadron Board Power Supply](https://github.com/user-attachments/assets/284cc06e-89f3-4205-a7f5-4f63055be284)
![VSD Squadron Mini Board Top View](https://github.com/user-attachments/assets/68118a48-bafa-45b8-9338-e4aad79f1d2c)
</details>


<details>
<summary> <h3>VSDSquadron Mini RISC-V Development Board</h3> </summary>


The VSDSquadron Mini RISC-V Development Board is a powerful yet compact embedded system platform designed to give developers an efficient and flexible environment for working with RISC-V based applications. Powered by the CH32V003F4U6 chip, this development board is optimized for high-performance computing tasks, supporting versatile peripherals and communication protocols.

Key Features and Specifications

Core Processor:

Processor: The board is driven by the CH32V003F4U6 chip, featuring a 32-bit RISC-V core based on the RV32EC instruction set. This architecture is ideal for applications requiring energy-efficient computing without sacrificing processing power.

Interrupt Management: Supports 2-level interrupt nesting, making it suitable for more complex, real-time embedded systems.

Clock Speed: Operates with a 24 MHz system clock, providing a stable and efficient environment for development.

Clock and Reset Systems:

Internal Oscillators:

A factory-trimmed 24 MHz RC oscillator provides the primary system clock, ensuring accuracy and stability.
A 128 kHz RC oscillator is also available for low-power or low-frequency applications.

External Clocking: The board offers an option to connect an external 24 MHz oscillator for applications requiring more precise or higher frequency timing.

General-Purpose I/O (GPIO):

Flexible I/O Options: The board offers 15 I/O ports spread across 3 groups of GPIO. These ports allow for extensive peripheral connectivity and can be mapped to external interrupts for event-driven programming.

High Expandability: These GPIO ports can be used for a wide variety of purposes, from simple digital input/output to more complex interfacing with sensors, displays, and other devices.

Communication Interfaces:

USART (Universal Asynchronous Receiver-Transmitter): Provides standard serial communication for interfacing with UART-based peripherals.

I2C (Inter-Integrated Circuit): A widely used protocol for communication with low-speed peripherals like sensors, EEPROMs, and RTCs.

SPI (Serial Peripheral Interface): Supports high-speed data exchange with SPI-based devices, ideal for interfacing with displays, SD cards, and other high-speed peripherals.

Memory:

SRAM: The board includes 2 KB of SRAM, used for volatile data storage during program execution.

Program Memory: 16 KB of CodeFlash is available for storing user programs.

Bootloader Memory: An additional 1920 bytes of memory is reserved for the bootloader, ensuring easy updates and reprogramming of the system.

On-board Programming:

Integrated Programming Solution: The CH32V305FBP6 chip on the board supports single-wire programming, meaning developers can program the chip without needing an external programmer or adapter.

USB-C Connectivity: Simply connect the board via the USB-C port to start programming and debugging, streamlining the development process and saving time on hardware setup.

Enhanced Development Workflow: The built-in programmer makes code deployment and debugging straightforward, enhancing development efficiency and reducing the need for additional hardware.

Kit Contents:

1 x VSDSquadron Mini RISC-V Development Board featuring the CH32V003F4U6 processor and all necessary components to begin development right out of the box.
Why Choose the VSDSquadron Mini RISC-V Development Board?
Cost-Effective and Efficient: With built-in programming features and a wide range of interfaces, this board provides exceptional value for both hobbyists and professional developers.

Versatile and Scalable: The rich set of GPIOs and communication protocols ensures the board can be used in a wide variety of applications, from simple I/O projects to more complex embedded systems.

Seamless Development: The integrated USB-C programmer and direct RISC-V support streamline the entire development process, making it easy to get started and quickly deploy custom code.

BLOCK DIAGRAM
![image](https://github.com/user-attachments/assets/f4f568f2-d25e-41ee-8398-5521f424224a)

Web Resources

For in-depth technical documentation and further details about the VSDSquadron Mini RISC-V Development Board and the CH32V003F4U6 RISC-V SoC, please refer to the following resources:

CH32V003F4U6 RISC-V SoC Datasheet: This datasheet provides comprehensive technical specifications, electrical characteristics, and functional descriptions of the CH32V003F4U6 chip. It’s a vital resource for understanding the processor’s performance and capabilities.

CH32V003F4U6 RISC-V SoC Reference Manual: The reference manual offers detailed insights into the programming model, system configuration, and architecture of the CH32V003F4U6. It’s an indispensable guide for developers looking to fully leverage the capabilities of this SoC.

These documents will equip you with the necessary knowledge to optimize the use of the VSDSquadron Mini RISC-V Development Board in your projects.

1.4 Board Overview

![VSD Squadron Mini RISC-V development board](https://github.com/user-attachments/assets/9519c12c-8542-4401-8c5d-ef7841ddf0fe)

The VSDSquadron Mini RISC-V Development Board is designed around the versatile CH32V003F4U6 RISC-V System on Chip (SoC), offering a comprehensive set of features to facilitate the development of high-performance embedded systems. Below is an overview of its most important capabilities:

Key Features:
On-board 24MHz RC Oscillator: The board integrates a 24 MHz factory-trimmed RC oscillator, ensuring stable and precise clocking for all system operations. This provides a reliable timing source for your embedded applications.

Flexible GPIO Ports: With 3 groups of GPIO ports offering a total of 15 I/O pins, the board allows you to easily interface with a wide range of peripherals. These pins can be configured for digital input/output and mapped to external interrupts for event-driven designs.

Comprehensive Communication Interfaces:

USART: Serial communication via USART enables seamless interaction with UART-based peripherals such as sensors, GPS modules, and other serial devices.
I2C: The I2C interface simplifies communication with low-speed devices like EEPROMs, sensors, and real-time clocks, allowing easy integration of various components.
SPI: The SPI interface provides high-speed data exchange, making it ideal for peripherals like SD cards, displays, and high-speed sensors.
Memory:

2KB SRAM: This provides volatile memory for dynamic data storage during program execution, ensuring smooth runtime operations.
16KB CodeFlash: A dedicated non-volatile memory for storing program code, ensuring the persistence of your application data even when the board is powered off.
Integrated On-board Programmer: The CH32V305FBP6 chip on the board supports single-wire programming, which allows for easy firmware updates and debugging. You can program the device directly through the USB-C connection, eliminating the need for external programming tools or adapters.


Form Factor
The VSDSquadron Mini RISC-V Development Board is designed to be compact yet powerful, making it ideal for embedded projects where space is at a premium. Below are the precise physical dimensions and key measurements:

Form Factor: 50.00 x 28.00 mm
Maximum Component Height (Top Side): 8 mm
Maximum Component Height (Bottom Side): 1 mm
These dimensions provide a versatile form factor, allowing you to easily integrate the board into a variety of custom enclosures or embedded systems.

![VSD Squadron Board Power Supply](https://github.com/user-attachments/assets/284cc06e-89f3-4205-a7f5-4f63055be284)
</details>

<details>
  <summary><h3>Lab Session 1:-</h3> Understood the basics of RISC-V And Openlane</summary>
  
  ![day1](https://github.com/user-attachments/assets/237d2b91-e75c-47d9-b430-3112beb819d6)

</details>

<details>
  <summary> <h3> Task 1</h3></summary>
  
  Installing RISC-V toolchain in Virtual Box
  
  ![Virtual Box for VSD Workshop](https://github.com/user-attachments/assets/e005aec7-3a2f-4b31-9798-eff27cef1dab)
  ![Virtual Box](https://github.com/user-attachments/assets/337daef5-02f4-448c-990e-fe6154a10b04)



  Creating a simple program in C to find sum of n numbers

  ![sum1ton_command](https://github.com/user-attachments/assets/f5cf99bd-c3a0-4aa5-b7d6-fe94f8c5ef47)
![writing c program](https://github.com/user-attachments/assets/c77cc4f4-d89d-49b2-830f-db1bd409e40e)

Main Function in RISCV Architecture

![riscv codes](https://github.com/user-attachments/assets/6f704b6a-a984-44c4-b6c6-6ecd24f75c11)
![main prg](https://github.com/user-attachments/assets/11d91534-fef6-40db-8247-baeac45173f7)
![verifying using calculator](https://github.com/user-attachments/assets/0e25064f-d6d2-4548-8544-1ea0e6a38a3d)

Running in Ofast Option in Riscv Architecture

![fast](https://github.com/user-attachments/assets/1a9418b0-64c3-4e04-ba3f-e01a68a77272)
![Verifying fast with calci](https://github.com/user-attachments/assets/111056ce-e31e-475d-8e5a-c24c6848928f)









</details>





