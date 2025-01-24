# Samsung-RISC-V-Workshop
**The RISC-V Workshop, certified by Samsung and VLSI Design, offers an immersive hands-on experience in RISC-V architecture, under the expert guidance of Kunal Ghosh. The workshop leverages the VSD Squadron Mini Board, a RISC-V-based development platform, designed to provide participants with real-world exposure to the design, implementation, and optimization of RISC-V processors.**

<b>Basic Details</b>

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
  <summary><h3>Lab Session 1:-</h3> Understood the basics of RISC-V </summary>
  
To write a Cprogram to multiply n numbers and converting it to the RISC-V Architecture

  ![multiply](https://github.com/user-attachments/assets/0e1aa642-58a3-4be2-8ac0-bc12ec7c9e75)

  Usage of RISC-V Architecture and Openlane
  
   ![day1](https://github.com/user-attachments/assets/237d2b91-e75c-47d9-b430-3112beb819d6)

  ![lab1](https://github.com/user-attachments/assets/67232ca4-bcba-4cbe-8244-60f3405be021)

  ![Day1 1](https://github.com/user-attachments/assets/b1e43809-7b39-49eb-ac7c-2b8ce267e267)
  
Floor Planning 

  ![floor plan](https://github.com/user-attachments/assets/4bcff685-8d4e-4f84-933e-e1a106c64b11)
  
cts

  ![cts](https://github.com/user-attachments/assets/3ef04f1b-cde9-4b9a-bf3d-2c13f8990a96)
  
Placement Analysis

  ![placement analysis](https://github.com/user-attachments/assets/fef565cc-1110-4d28-8df1-d7c44f9b5015)
  
Routing

  ![routing](https://github.com/user-attachments/assets/1a84ba9a-4e87-4610-816f-f838355a561d)


</details>

<details>
  <summary> <h3> Task 1:</h3> Install the RISC-V tool by setting up a Virtual Machine in Oracle Virtual Box. Converting C programs to RISC-V Architecture</summary>
  
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

<details>
  <summary> <h3> Task 2: </h3> Writing a simple c program and compiling it using RISCV GCC/SPIKE and collecting the RISCV object dump for both -O1 and -Ofast </summary>
  

  Main function of Sum of n numbers in -Ofast Option in RISCV64:

  ![Main function to find sum of n no in Ofast](https://github.com/user-attachments/assets/5b97ee62-c985-42ec-a399-425943b62743)

  Debugging   Sum of n numbers in -Ofast in SPIKE:

  ![Running and debugging addition of n no using spike ](https://github.com/user-attachments/assets/cf7da192-6de5-4922-bb6b-8484523faa30)

  Simple C Program to find Product of n numbers:

  ![c program to find product of n numbers](https://github.com/user-attachments/assets/eac9441a-22c4-4e19-9023-8a17a9165192)

  Main function of product of n numbers in -O1 Option in RISCV64:

  ![Main function -o1 for product of n no](https://github.com/user-attachments/assets/77de1ecf-3967-46be-a4a5-495109d06ceb)

  Debugging product of n numbers in -O1 in SPIKE:

  ![debugging -O1 for product of n no  in SPIKE](https://github.com/user-attachments/assets/d4aba074-15a2-4d32-bc13-62cc44a3279d)

  Main Function of product of n numbers in -Ofast Option in RISCV64:

  ![Main function for product of n no  in Ofast](https://github.com/user-attachments/assets/bdc12022-fbb4-40ea-9ddc-81b42dfe956a)

  Debugging product of n numbers in -Ofast in SPIKE:

  ![Debugging -Ofast in SPIKE](https://github.com/user-attachments/assets/fb34b077-ca26-4e5a-93f5-57b8d161febe)


</details>

<details>

  <summary> <h3> Task 3: </h3> Review the RISC-V software documentation to understand the R, I, S, B, U, and J instruction types. Then, from the riscv-objdump output of your application code, identify 15 unique 
                                RISC-V instructions and determine their exact 32-bit instruction codes in the respective formats.</summary>


                                

 <h3> R,I,S,B,U and J Instruction Types</h3>

  In the RISC-V instruction set architecture (ISA), instructions are divided into various types based on their format. The specific instruction types you asked about—R, I, S, B, U, and J—refer to different formats used in the encoding of instructions. Here's a brief overview of each:

### 1. **R-type (Register-type)**  
R-type instructions perform operations between registers. These instructions usually involve arithmetic or logical operations.

- **Format:**
  ```
  | funct7 | rs2 | rs1 | funct3 | rd | opcode |
  ```

- **Fields:**
  - `funct7`: 7 bits for a function code, which helps determine the specific operation.
  - `rs2`: 5 bits for the second source register.
  - `rs1`: 5 bits for the first source register.
  - `funct3`: 3 bits for a function code to distinguish between different types of operations.
  - `rd`: 5 bits for the destination register.
  - `opcode`: 7 bits specifying the operation (like `add`, `sub`, `and`, `or`).

- **Examples:**
  - `add`, `sub`, `mul`, `and`, `or`, `sll`, etc.

### 2. **I-type (Immediate-type)**  
I-type instructions involve an immediate value (constant) and a register. They are often used for operations involving an immediate value or loading data from memory.

- **Format:**
  ```
  | imm[11:0] | rs1 | funct3 | rd | opcode |
  ```

- **Fields:**
  - `imm[11:0]`: 12-bit immediate value.
  - `rs1`: 5 bits for the source register.
  - `funct3`: 3 bits for a function code.
  - `rd`: 5 bits for the destination register.
  - `opcode`: 7 bits for the operation code.

- **Examples:**
  - `addi`, `lw`, `jalr`, `xori`, `slti`, etc.

### 3. **S-type (Store-type)**  
S-type instructions are used for store operations, where data is written to memory.

- **Format:**
  ```
  | imm[11:5] | rs2 | rs1 | funct3 | imm[4:0] | opcode |
  ```

- **Fields:**
  - `imm[11:5]`: 7 bits of the immediate value (upper part).
  - `rs2`: 5 bits for the second source register (data to be stored).
  - `rs1`: 5 bits for the base register (address).
  - `funct3`: 3 bits for specifying the store operation.
  - `imm[4:0]`: 5 bits of the immediate value (lower part).
  - `opcode`: 7 bits for the operation code.

- **Examples:**
  - `sw`, `sh`, `sb` (store word, store halfword, store byte).

### 4. **B-type (Branch-type)**  
B-type instructions are used for conditional branching.

- **Format:**
  ```
  | imm[12] | imm[10:5] | rs2 | rs1 | funct3 | imm[4:1] | imm[11] | opcode |
  ```

- **Fields:**
  - `imm`: Immediate value split into several fields.
  - `rs2`: 5 bits for the second source register.
  - `rs1`: 5 bits for the first source register (comparison).
  - `funct3`: 3 bits for specifying the branch condition.
  - `opcode`: 7 bits for the operation code.

- **Examples:**
  - `beq`, `bne`, `blt`, `bge`, `bltu`, `bgeu`.

### 5. **U-type (Upper immediate-type)**  
U-type instructions are used for operations that involve large immediate values (usually for addressing or setting a large constant).

- **Format:**
  ```
  | imm[31:12] | rd | opcode |
  ```

- **Fields:**
  - `imm[31:12]`: 20-bit immediate value.
  - `rd`: 5 bits for the destination register.
  - `opcode`: 7 bits for the operation code.

- **Examples:**
  - `lui` (Load Upper Immediate), `auipc` (Add Upper Immediate to PC).

### 6. **J-type (Jump-type)**  
J-type instructions are used for jump operations with a large offset.

- **Format:**
  ```
  | imm[20] | imm[10:1] | imm[11] | imm[19:12] | rd | opcode |
  ```

- **Fields:**
  - `imm`: A 21-bit immediate value split into several fields.
  - `rd`: 5 bits for the destination register (used in `jal`).
  - `opcode`: 7 bits for the operation code.

- **Examples:**
  - `jal` (Jump and Link).

### Summary:
- **R-type**: Register-to-register operations (arithmetic, logical).
- **I-type**: Immediate operations or load instructions.
- **S-type**: Store operations (write to memory).
- **B-type**: Branch (conditional jumps).
- **U-type**: Large immediate values (addressing or constants).
- **J-type**: Jump with a large offset.

These instruction types help structure the encoding of instructions and optimize the processing of different kinds of operations in the RISC-V architecture.

<h3>RISC_V-objdump</h3>

![RISCV obj dump](https://github.com/user-attachments/assets/ecffa976-c761-4bb2-86eb-d5788698ea62)


Unique RISC_V Instructions

![Unique RISC_V Instructions](https://github.com/user-attachments/assets/10ab84b3-d696-48c2-9524-54fba381abb7)

<h3>32 Bit Instruction Code For Unique RISC_V Instructions</h3>

<h3>1) lui a2,0x376</h3>


The instruction `lui a2, 0x376` is a **U-type** instruction in RISC-V. Here's how to determine the exact 32-bit instruction code for it.

### Breakdown of the `lui` instruction:
- **Opcode** for `lui` is `0110111` (7 bits).
- **rd** is the destination register, which is `a2`. In RISC-V, `a2` corresponds to register `x12`. So, `rd = 12`, which is `01100` in binary (5 bits).
- **Immediate** is `0x376`. The `lui` instruction loads the upper 20 bits of a register with the immediate value, shifting it to the left by 12 bits. So, we have:
  - **Immediate value** = `0x376` (or `0000 0011 0111 0110` in binary)
  - The full immediate for `lui` is `0x376000` (i.e., `0000 0011 0111 0110 0000 0000` in binary).

### Final Instruction Encoding:
- **Immediate (bits 31:12)**: `0000 0011 0111 0110 0000 0000` (20 bits)
- **rd**: `01100` (5 bits for `a2`)
- **opcode**: `0110111` (7 bits for `lui`)

### 32-bit Instruction Code:
Now, we can combine all the fields:

```
| imm[31:12]      | rd  | opcode |
| 0000 0011 0111 0110 0000 0000 | 01100 | 0110111 |
```

This gives us the 32-bit machine code:

```
0000 0011 0111 0110 0000 0000 01100 0110111
```

### Final 32-bit Machine Code:
```
0x00037637
```

So, the exact 32-bit instruction code for `lui a2, 0x376` is **`0x00037637`**.


<h3>2) lui a0,0x21</h3>

   The instruction `lui a0, 0x21` is a **U-type** instruction in RISC-V. Let's break down the encoding of this instruction.

### Breakdown of the `lui` instruction:
- **Opcode** for `lui` is `0110111` (7 bits).
- **rd** is the destination register, which is `a0`. In RISC-V, `a0` corresponds to register `x10`. So, `rd = 10`, which is `01010` in binary (5 bits).
- **Immediate** is `0x21`. The `lui` instruction loads the upper 20 bits of the register with the immediate value, shifting it to the left by 12 bits. So, we have:
  - **Immediate value** = `0x21`, which in binary is `0000 0010 0001`.
  - The full immediate for `lui` is `0x21000` (i.e., `0000 0010 0001 0000 0000 0000` in binary).

### Final Instruction Encoding:
- **Immediate (bits 31:12)**: `0000 0010 0001 0000 0000 0000` (20 bits).
- **rd**: `01010` (5 bits for `a0`).
- **opcode**: `0110111` (7 bits for `lui`).

### 32-bit Instruction Code:
Now, we can combine all the fields:

```
| imm[31:12]      | rd  | opcode |
| 0000 0010 0001 0000 0000 0000 | 01010 | 0110111 |
```

This gives us the 32-bit machine code:

```
0000 0010 0001 0000 0000 0000 01010 0110111
```

### Final 32-bit Machine Code:
```
0x00221037
```

So, the exact 32-bit instruction code for `lui a0, 0x21` is **`0x00221037`**.


<h3>3) addi sp,sp,-16</h3>

   The instruction `addi sp, sp, -16` is an **I-type** instruction in RISC-V. Let's break it down to determine the exact 32-bit instruction code.

### Breakdown of the `addi` instruction:
- **`addi`** is an immediate type instruction, which has the format:
  ```
  imm[11:0] | rs1 | funct3 | rd | opcode
  ```
- **Opcode** for `addi` is `0010011` (7 bits).
- **`rs1`** is the source register, which is `sp` (stack pointer). In RISC-V, `sp` corresponds to register `x2`. So, `rs1 = 2`, which is `00010` in binary (5 bits).
- **`rd`** is the destination register, which is also `sp`. So, `rd = 2` (since both source and destination are `sp`), which is `00010` in binary (5 bits).
- **Immediate** is `-16`. The immediate value needs to be represented as a 12-bit signed value:
  - `-16` in binary (12 bits) is `1111 0000 0000` (2's complement representation).

### Final Instruction Encoding:
Now, let's assemble all the fields:

- **Immediate (imm[11:0])**: `1111 0000 0000` (12 bits for `-16`).
- **rs1**: `00010` (5 bits for `sp`).
- **funct3**: `000` (3 bits for `addi`).
- **rd**: `00010` (5 bits for `sp`).
- **opcode**: `0010011` (7 bits for `addi`).

### 32-bit Instruction Code:
Now, combining all the fields together:

```
| imm[11:0]    | rs1  | funct3 | rd   | opcode |
| 1111 0000 0000 | 00010 | 000 | 00010 | 0010011 |
```

This results in the 32-bit machine code:

```
1111 0000 0000 00010 000 00010 0010011
```

### Final 32-bit Machine Code:
```
0xfff30313
```

So, the exact 32-bit instruction code for `addi sp, sp, -16` is **`0xfff30313`**.


<h3> 4) addi a2,a2,-256 </h3>


Let's break down the instruction `addi a2, a2, -256` step-by-step to determine its exact 32-bit machine code.

### Breakdown of the `addi` Instruction:
- **Instruction**: `addi a2, a2, -256`
  - **`addi`** is an immediate-type instruction in RISC-V (I-type format).
  - The general format for I-type instructions is:
    ```
    imm[11:0] | rs1 | funct3 | rd | opcode
    ```
  - **`opcode`** for `addi` is `0010011` (7 bits).
  - **`rs1`** is the source register, which is `a2`. In RISC-V, `a2` corresponds to register `x12`. So, `rs1 = 12`, which is `01100` in binary (5 bits).
  - **`rd`** is the destination register, which is also `a2`. So, `rd = 12` (same as `rs1`), which is `01100` in binary (5 bits).
  - **Immediate** is `-256`. To represent this immediate in 12 bits using two's complement:
    - `-256` in binary (12-bit two's complement) is `111111111000` (12 bits).
  
### Final Instruction Encoding:
Now, let's break down the encoding based on these fields:

1. **Immediate (imm[11:0])**: `111111111000` (binary representation of `-256`).
2. **rs1**: `01100` (binary representation of `a2`).
3. **funct3**: `000` (for the `addi` operation).
4. **rd**: `01100` (binary representation of `a2`).
5. **opcode**: `0010011` (opcode for the `addi` instruction).

### 32-bit Instruction Code:
Now, combine all the fields into the 32-bit instruction:

```
| imm[11:0]   | rs1   | funct3 | rd   | opcode |
| 111111111000 | 01100 | 000    | 01100 | 0010011 |
```

This is the binary representation:
```
111111111000 01100 000 01100 0010011
```

### Final 32-bit Machine Code:
The final 32-bit machine code for `addi a2, a2, -256` is:
```
0xfff30313
```

### Conclusion:
The exact 32-bit instruction code for `addi a2, a2, -256` is **`0xfff30313`**.

<h3> 5) li a1,10</h3>

The instruction `li a1, 10` is a **load immediate** instruction, but in RISC-V, `li` is typically implemented using the `lui` (Load Upper Immediate) and `addi` (Add Immediate) instructions, since RISC-V does not have a dedicated `li` instruction.

To determine the exact 32-bit machine code for `li a1, 10`, we will need to break it down into valid RISC-V instructions.

### Step 1: Break down `li a1, 10` using RISC-V instructions
In order to load the immediate value `10` into register `a1` (which corresponds to register `x11`), we can use two instructions:
1. **`lui a1, 0`**: Load Upper Immediate. This will load the upper 20 bits of `a1` with `0`. The lower 12 bits are set to zero, so the immediate becomes `0x00000000`.
2. **`addi a1, a1, 10`**: Add Immediate. This will add `10` to the value in `a1`, effectively loading `10` into `a1`.

### Step 2: Determine the 32-bit instruction code for each instruction

#### 1. `lui a1, 0`
- **Opcode for `lui`** is `0110111` (7 bits).
- **`rd`** (destination register) is `a1`, which corresponds to register `x11`. So, `rd = 11`, which is `01011` in binary (5 bits).
- **Immediate** is `0x00000` (upper 20 bits).
  
**Instruction Encoding for `lui a1, 0`:**
- **Immediate (imm[31:12])**: `00000000000000000000` (20 bits).
- **`rd`**: `01011` (5 bits for `a1`).
- **Opcode**: `0110111` (7 bits for `lui`).

The 32-bit instruction binary encoding is:

```
00000000000000000000 01011 0110111
```

This results in the machine code:

```
0x00005037
```

#### 2. `addi a1, a1, 10`
- **Opcode for `addi`** is `0010011` (7 bits).
- **`rs1`** (source register) is `a1`, which corresponds to register `x11`. So, `rs1 = 11`, which is `01011` in binary (5 bits).
- **`rd`** (destination register) is `a1`, which is `01011` in binary (5 bits).
- **Immediate** is `10`, which is `000000001010` in binary (12 bits).

**Instruction Encoding for `addi a1, a1, 10`:**
- **Immediate (imm[11:0])**: `000000001010` (12 bits).
- **`rs1`**: `01011` (5 bits for `a1`).
- **`funct3`**: `000` (3 bits for `addi`).
- **`rd`**: `01011` (5 bits for `a1`).
- **Opcode**: `0010011` (7 bits for `addi`).

The 32-bit instruction binary encoding is:

```
000000001010 01011 000 01011 0010011
```

This results in the machine code:

```
0x00030313
```

### Step 3: Combine the Instructions
To load the immediate value `10` into `a1`, we will need two instructions:
1. `lui a1, 0x0` → `0x00005037`
2. `addi a1, a1, 10` → `0x00030313`

### Final Conclusion:
The exact 32-bit instruction codes to implement `li a1, 10` are:
1. **`0x00005037`** for `lui a1, 0`
2. **`0x00030313`** for `addi a1, a1, 10`


<h3> 6) addi a0,a0,384</h3>


The instruction `addi a0, a0, 384` is an **I-type** instruction in RISC-V. Let's break down the instruction to determine its exact 32-bit machine code.

### Breakdown of the `addi` Instruction:
- **`addi`** is an immediate-type instruction in RISC-V, and its format is as follows:
  ```
  imm[11:0] | rs1 | funct3 | rd | opcode
  ```
- **Opcode** for `addi` is `0010011` (7 bits).
- **`rs1`** is the source register, which is `a0`. In RISC-V, `a0` corresponds to register `x10`. So, `rs1 = 10`, which is `01010` in binary (5 bits).
- **`rd`** is the destination register, which is also `a0`. So, `rd = 10` (same as `rs1`), which is `01010` in binary (5 bits).
- **Immediate** is `384`. To represent this immediate in 12 bits:
  - `384` in binary is `0000000110000000` (12 bits).

### Final Instruction Encoding:
Now, let's encode the instruction step-by-step:

1. **Immediate (imm[11:0])**: `0000000110000000` (12 bits for `384`).
2. **rs1**: `01010` (5 bits for `a0`).
3. **funct3**: `000` (3 bits for `addi`).
4. **rd**: `01010` (5 bits for `a0`).
5. **opcode**: `0010011` (7 bits for `addi`).

### 32-bit Instruction Code:
Now, combine all the fields:

```
| imm[11:0]        | rs1   | funct3 | rd   | opcode |
| 0000000110000000  | 01010 | 000    | 01010 | 0010011 |
```

This results in the following 32-bit binary encoding:

```
0000000110000000 01010 000 01010 0010011
```

### Final 32-bit Machine Code:
The final 32-bit machine code for `addi a0, a0, 384` is:

```
0x00030313
```

### Conclusion:
The exact 32-bit instruction code for `addi a0, a0, 384` is **`0x00030313`**.


<h3> 7) sd ra,8(sp)</h3>

The instruction `sd ra, 8(sp)` is a **S-type** instruction in RISC-V. It stores a 64-bit value (from the `ra` register) into memory at the address computed as `sp + 8`.

Let's break down the instruction step-by-step to determine the exact 32-bit instruction code. Since the `sd` instruction is for storing 64-bit data, it will be encoded as two 32-bit `store` instructions in RISC-V (one for each 32-bit half of the 64-bit value).

### Breakdown of the `sd` Instruction:

1. **`sd` (Store Double) Instruction**:
   - **Opcode** for `sd` is `0100011` (7 bits) because it is a store instruction.
   - **funct3** for `sd` is `011` (3 bits), which indicates that this is a store double (64-bit).
   - **`rs1`** is the base register, which is `sp`. In RISC-V, `sp` corresponds to register `x2`. So, `rs1 = 2`, which is `00010` in binary (5 bits).
   - **`rs2`** is the source register, which is `ra`. In RISC-V, `ra` corresponds to register `x1`. So, `rs2 = 1`, which is `00001` in binary (5 bits).
   - **Immediate** is `8` (the offset from `sp`). The immediate value must be encoded as a 12-bit signed value. Since `8` is positive, its 12-bit representation is `000000001000`.

### Encoding the First 32-bit Half:
Since the `sd` instruction stores 64-bits, it will require two `store` instructions (one for the lower 32-bits and one for the upper 32-bits of the 64-bit value). 

#### 1st `store` instruction (lower 32-bits):

- **Immediate (imm[11:5])**: `0000000` (7 bits from the lower 7 bits of the immediate `8`).
- **`rs2`** (value to store, `ra`): `00001` (5 bits for `x1`).
- **`rs1`** (base register, `sp`): `00010` (5 bits for `x2`).
- **funct3**: `011` (3 bits for `sd`).
- **Immediate (imm[4:0])**: `01000` (5 bits for the lower 5 bits of the immediate `8`).
- **Opcode**: `0100011` (7 bits for store instructions).

So, the first instruction's 32-bit binary encoding is:

```
imm[11:5] | rs2 | rs1 | funct3 | imm[4:0] | opcode
0000000    | 00001 | 00010 | 011    | 01000    | 0100011
```

This gives us the binary instruction:

```
0000000 00001 00010 011 01000 0100011
```

This results in the machine code:

```
0x00010223
```

#### 2nd `store` instruction (upper 32-bits):
The second store instruction will have the same format, but this time for the upper 32-bits of the 64-bit value. Since the `sd` instruction is storing a full 64-bit value, the offset is the same for both instructions, but we need to adjust the immediate for the second half of the 64-bit value.

The second store instruction will have the same binary structure, but this time it’s still storing the same value at the same offset (`sp + 8`), but the encoding changes for the upper half (because it's part of a 64-bit store).

The second instruction encoding should be similar:

```
0x00010223
```

### Final Conclusion:

The exact 32-bit instruction code for the first `sd ra, 8(sp)` store instruction is:

```
0x00010223
```

<h3> 8) jal ra,1040c </h3>

The instruction `jal ra, 1040c` is a **J-type** instruction in RISC-V. The `jal` (Jump and Link) instruction is used for jumping to a target address, and it saves the return address in the `ra` (return address) register.

### Breakdown of the `jal` Instruction:
- **Opcode** for `jal` is `1101111` (7 bits).
- **rd** is the destination register where the return address will be stored. In this case, `rd` is `ra`, which corresponds to register `x1`. So, `rd = 1`, which is `00001` in binary (5 bits).
- **Immediate** is the offset to the target address. The `jal` instruction uses a 20-bit signed immediate that represents the distance to jump from the current instruction.

The immediate value `1040c` is given in hexadecimal, which is `0x1040c = 66,044` in decimal. This is the address offset to jump to.

### Encoding the `jal` Instruction:
1. **Immediate (20-bit offset)**:
   The immediate for `jal` is a 20-bit signed immediate. The offset value needs to be split into specific fields:
   - The offset is `1040c` (66,044 in decimal). This will be encoded in the 20-bit signed immediate field for `jal`.
   
   In binary, `1040c` is `0001 0000 0100 0000 1100`. When splitting into the appropriate bit fields for a `jal` instruction:
   - `imm[20]` = 0 (bit 20)
   - `imm[10:1]` = `0001000001` (bits 10-1)
   - `imm[11]` = 0 (bit 11)
   - `imm[19:12]` = `00000010` (bits 19-12)

   The final bit representation for the immediate is:

   ```
   imm[20] | imm[10:1] | imm[11] | imm[19:12]
   0       | 0001000001 | 0       | 00000010
   ```

2. **rd**: `ra` is the return address register, which corresponds to `x1`, so `rd = 1`, which is `00001` in binary (5 bits).

3. **Opcode**: `jal` opcode is `1101111` (7 bits).

### Putting It All Together:

Now, combine the fields into a 32-bit instruction:

```
| imm[20] | imm[10:1]   | imm[11] | imm[19:12] | rd    | opcode |
| 0       | 0001000001  | 0       | 00000010   | 00001 | 1101111 |
```

This gives the following 32-bit instruction binary:

```
0 0001000001 0 00000010 00001 1101111
```

### Final 32-bit Machine Code:
Converting the binary into hexadecimal:

```
0000 0001 0000 0001 0000 0010 0000 0001 1101 1111
```

This results in the machine code:

```
0x000102ff
```

### Conclusion:
The exact 32-bit instruction code for `jal ra, 1040c` is **`0x000102ff`**.

<h3> 9) ld ra,8(sp) </h3>

The instruction `ld ra, 8(sp)` is a **I-type** instruction in RISC-V for loading a 64-bit value from memory into the `ra` (return address) register. The `ld` instruction is used to load double words (64 bits).

Let's break down the `ld` instruction and determine its exact 32-bit machine code.

### Breakdown of the `ld` Instruction:
- **Opcode** for `ld` is `0000011` (7 bits), since it is a load instruction.
- **funct3** for `ld` is `011` (3 bits), indicating that this is a load double word (64 bits).
- **rs1** is the base register, which is `sp` (stack pointer). In RISC-V, `sp` corresponds to register `x2`. So, `rs1 = 2`, which is `00010` in binary (5 bits).
- **rd** is the destination register, which is `ra`. In RISC-V, `ra` corresponds to register `x1`. So, `rd = 1`, which is `00001` in binary (5 bits).
- **Immediate** is `8`, which is the offset from the base register `sp` (the memory address is `sp + 8`).

### Instruction Encoding:
The I-type instruction format is:
```
imm[11:0] | rs1 | funct3 | rd | opcode
```

Let's encode each part:

1. **Immediate (imm[11:0])**: `8` in binary is `000000001000` (12 bits).
2. **rs1**: `00010` (5 bits for `sp`).
3. **funct3**: `011` (3 bits for `ld`).
4. **rd**: `00001` (5 bits for `ra`).
5. **opcode**: `0000011` (7 bits for `ld`).

### 32-bit Instruction Encoding:
Now, let's combine all the fields:

```
imm[11:0]   | rs1  | funct3 | rd   | opcode
000000001000 | 00010 | 011    | 00001 | 0000011
```

This gives the following 32-bit instruction binary:

```
000000001000 00010 011 00001 0000011
```

### Final 32-bit Machine Code:
Now, let's convert the binary encoding into hexadecimal:

```
0000 0000 1000 0001 1011 0000 0011
```

This results in the machine code:

```
0x0003033f
```

### Conclusion:
The exact 32-bit instruction code for `ld ra, 8(sp)` is **`0x0003033f`**.

<h3> 10) li a0,0 </h3>

The instruction `li a0, 0` is a **Load Immediate** instruction, but in RISC-V, there is no direct `li` instruction. Instead, the `li` instruction is typically implemented using a combination of the `lui` (Load Upper Immediate) and `addi` (Add Immediate) instructions.

To load an immediate value of `0` into register `a0`, we can simply use the following two instructions:
1. **`lui a0, 0`**: This will load the upper 20 bits of `a0` with `0`, effectively setting the upper 20 bits of `a0` to `0`.
2. **`addi a0, a0, 0`**: This will add `0` to the value in `a0` (which is already `0` from the `lui` instruction), ensuring that `a0` remains `0`.

### Step 1: Break down `lui a0, 0`

#### `lui` (Load Upper Immediate) encoding:
- **Opcode**: `0110111` (7 bits for `lui`).
- **rd**: `a0`, which is `x10`. So, `rd = 10`, which is `01010` in binary (5 bits).
- **Immediate**: `0x00000` (upper 20 bits are all zero).

The instruction format for `lui` is:
```
| imm[31:12] | rd    | opcode |
| 00000000000000000000 | 01010 | 0110111 |
```

This results in the 32-bit instruction:
```
0x00005037
```

### Step 2: Break down `addi a0, a0, 0`

#### `addi` (Add Immediate) encoding:
- **Opcode**: `0010011` (7 bits for `addi`).
- **rs1**: `a0`, which corresponds to `x10`. So, `rs1 = 10`, which is `01010` in binary (5 bits).
- **rd**: `a0`, which is `x10`. So, `rd = 10`, which is `01010` in binary (5 bits).
- **Immediate**: `0` (12-bit signed immediate).

The instruction format for `addi` is:
```
| imm[11:0] | rs1   | funct3 | rd   | opcode |
| 000000000000 | 01010 | 000    | 01010 | 0010011 |
```

This results in the 32-bit instruction:
```
0x00030313
```

### Final Conclusion:
To load the value `0` into `a0`, we need to use two instructions:

1. **`lui a0, 0`**: `0x00005037`
2. **`addi a0, a0, 0`**: `0x00030313`

Thus, the exact 32-bit machine code for `li a0, 0` is a combination of the two instructions:
- **`0x00005037`** for `lui a0, 0`
- **`0x00030313`** for `addi a0, a0, 0`

Both instructions work together to set the value of `a0` to `0`.

<h3> 11) addi sp,sp,16</h3>

The instruction `addi sp, sp, 16` is an **I-type** instruction in RISC-V, where an immediate value is added to a register value and stored in another register.

Let's break down the instruction to determine its exact 32-bit machine code.

### Breakdown of the `addi` Instruction:
- **Opcode** for `addi` is `0010011` (7 bits).
- **`rs1`** is the source register, which is `sp` (stack pointer). In RISC-V, `sp` corresponds to register `x2`. So, `rs1 = 2`, which is `00010` in binary (5 bits).
- **`rd`** is the destination register, which is also `sp` in this case. So, `rd = 2`, which is `00010` in binary (5 bits).
- **Immediate** is `16`. To represent this immediate in 12 bits:
  - `16` in binary is `000000010000` (12 bits).

### Instruction Encoding:
The `addi` instruction format is:

```
imm[11:0] | rs1 | funct3 | rd | opcode
```

Now, let's encode the parts:
- **Immediate (imm[11:0])**: `000000010000` (12 bits for `16`).
- **rs1**: `00010` (5 bits for `sp`).
- **funct3**: `000` (3 bits for `addi`).
- **rd**: `00010` (5 bits for `sp`).
- **opcode**: `0010011` (7 bits for `addi`).

### Final Instruction Encoding:

Now, combine all the fields into a 32-bit instruction:

```
| imm[11:0]   | rs1  | funct3 | rd   | opcode |
| 000000010000 | 00010 | 000    | 00010 | 0010011 |
```

This gives the following 32-bit binary instruction:

```
000000010000 00010 000 00010 0010011
```

### Final 32-bit Machine Code:
Now, let's convert the binary encoding into hexadecimal:

```
0000 0001 0000 0010 000 0001 0011
```

This results in the machine code:

```
0x00030313
```

### Conclusion:
The exact 32-bit instruction code for `addi sp, sp, 16` is **`0x00030313`**.

<h3> 12) ret </h3>

The instruction `ret` in RISC-V is essentially a **JALR** (Jump and Link Register) instruction with a zero offset. It is used to return from a function, using the return address stored in the `ra` register (which is `x1` in RISC-V).

### Breakdown of the `ret` Instruction:
- The `ret` instruction is equivalent to:
  ```
  jalr x0, 0(ra)
  ```
  Where `x0` is the destination register (which discards the return address), `ra` is the base register containing the return address, and the immediate offset is `0`.
  
  In other words, the instruction does the following:
  - It jumps to the address stored in `ra` (the return address register) with an offset of `0`, effectively returning from the function.

### RISC-V JALR (Jump and Link Register) Encoding:
The `jalr` instruction is an I-type instruction with the following format:
```
imm[11:0] | rs1  | funct3 | rd   | opcode
```

For `jalr x0, 0(ra)`:
- **Opcode** for `jalr` is `1100111` (7 bits).
- **`rs1`** is `ra`, which corresponds to register `x1`. So, `rs1 = 1`, which is `00001` in binary (5 bits).
- **`rd`** is `x0`, which corresponds to register `x0`. So, `rd = 0`, which is `00000` in binary (5 bits).
- **Immediate** is `0`, which is encoded as `000000000000` (12 bits).

### Final Instruction Encoding:
Now, we can assemble the 32-bit instruction:

```
| imm[11:0] | rs1   | funct3 | rd    | opcode |
| 000000000000 | 00001 | 000    | 00000 | 1100111 |
```

This gives the following 32-bit binary encoding:

```
000000000000 00001 000 00000 1100111
```

### Final 32-bit Machine Code:
Converting the binary encoding to hexadecimal:

```
0000 0000 0000 0001 000 0000 1100 1111
```

This results in the machine code:

```
0x00008067
```

### Conclusion:
The exact 32-bit instruction code for the `ret` instruction in RISC-V is **`0x00008067`**.

<h3> 13) auipc a5,0xffff0</h3>

The instruction `auipc a5, 0xffff0` is an **U-type** instruction in RISC-V. The `auipc` instruction (Add Upper Immediate to PC) is used to add a 20-bit immediate value to the current Program Counter (PC) and store the result in a register.

### Breakdown of the `auipc` Instruction:
The `auipc` instruction has the following format:
```
imm[31:12] | rd    | opcode
```

Where:
- **Opcode** for `auipc` is `0010111` (7 bits).
- **rd** is the destination register where the result is stored. In this case, `rd` is `a5`, which corresponds to register `x15`. So, `rd = 15`, which is `01111` in binary (5 bits).
- **Immediate** is a 20-bit value. In this case, the immediate value is `0xffff0`, which is `1048560` in decimal. We need to represent this as a 20-bit signed value.

### Encoding the Immediate:
The immediate value is `0xffff0`. In binary, `0xffff0` is represented as:
```
0000 1111 1111 1111 0000
```

We can split this immediate value into two parts:
- **imm[31:12]**: `00001111111111111111` (upper 20 bits).
- **rd**: `a5` corresponds to `x15`, which is `01111` in binary (5 bits).
- **opcode**: `0010111` (7 bits for `auipc`).

### Final Instruction Encoding:
Now, we can assemble the instruction with the fields:

```
| imm[31:12]          | rd    | opcode |
| 00001111111111111111 | 01111 | 0010111 |
```

This results in the following 32-bit binary encoding:

```
00001111111111111111 01111 0010111
```

### Final 32-bit Machine Code:
Converting the binary encoding to hexadecimal:

```
0000 1111 1111 1111 1111 0111 0010 1111
```

This results in the machine code:

```
0x0fff5073
```

### Conclusion:
The exact 32-bit instruction code for `auipc a5, 0xffff0` is **`0x0fff5073`**.

<h3> 14) addi a5,a5,-224</h3>


The instruction `addi a5, a5, -224` is an **I-type** instruction in RISC-V. The `addi` instruction is used to add an immediate value to a register and store the result in another register.

### Breakdown of the `addi` Instruction:
The `addi` instruction format is:

```
imm[11:0] | rs1 | funct3 | rd | opcode
```

Where:
- **Opcode** for `addi` is `0010011` (7 bits).
- **`rs1`** is the source register, which is `a5`. In RISC-V, `a5` corresponds to register `x15`. So, `rs1 = 15`, which is `01111` in binary (5 bits).
- **`rd`** is the destination register, which is also `a5`. So, `rd = 15`, which is `01111` in binary (5 bits).
- **Immediate** is `-224`. To represent this as a 12-bit signed immediate:
  - `-224` in decimal is represented in binary as `1111111110000000` in two's complement (12 bits).

### Immediate Encoding:
For `addi a5, a5, -224`, the immediate is `-224`. In two's complement (12-bit) binary:
```
-224 = 1111111110000000 (12 bits)
```

### Putting It All Together:
Now, we can assemble the 32-bit instruction by combining the fields:

```
| imm[11:0]       | rs1   | funct3 | rd    | opcode |
| 1111111110000000 | 01111 | 000    | 01111 | 0010011 |
```

This gives the following 32-bit binary encoding:

```
111111111000 01111 000 01111 0010011
```

### Final 32-bit Machine Code:
Converting the binary encoding to hexadecimal:

```
1111 1111 1000 0111 100 0111 0010 0111
```

This results in the machine code:

```
0xfff30313
```

### Conclusion:
The exact 32-bit instruction code for `addi a5, a5, -224` is **`0xfff30313`**.

<h3> 15) beqz a5,100f8 </h3>

The instruction `beqz a5, 100f8` is a **B-type** instruction in RISC-V. It is a conditional branch instruction that checks if a register (`a5` in this case) is equal to zero, and if so, it will branch to the target address specified by the immediate.

### Breakdown of the `beqz a5, 100f8` Instruction:
The `beqz` (branch if equal to zero) instruction can be interpreted as:

```
beq a5, x0, 100f8
```

Which means "if the value in register `a5` is equal to `0`, branch to the address `PC + 100f8`."

### B-Type Instruction Format:
The format for the **B-type** instruction is:

```
imm[12] | imm[10:5] | rs2  | rs1  | funct3 | imm[4:1] | imm[11] | opcode
```

Where:
- **opcode** for `beq` is `1100011` (7 bits).
- **funct3** for `beq` is `000` (3 bits).
- **rs1** is the first register, which is `a5`. In RISC-V, `a5` corresponds to register `x15`. So, `rs1 = 15`, which is `01111` in binary (5 bits).
- **rs2** is the second register, which is `x0`. So, `rs2 = 0`, which is `00000` in binary (5 bits).
- **Immediate** is the branch offset, which is `100f8`. We need to calculate the offset relative to the current `PC` (Program Counter).

### Step 1: Calculate the Immediate Offset
The target address for the branch is `100f8`, which is the offset from the current instruction. Since the immediate is encoded in the instruction as a 12-bit signed value, the value needs to be calculated relative to the current instruction's address.

Assume that the current instruction is at address `PC`. The offset for `100f8` is the target address minus the address of the next instruction (`PC + 4`), because the `beq` instruction uses **word**-aligned addresses.

```
Immediate = target - (PC + 4)
```

So, the immediate is:
```
100f8 - 4 = 100f4
```

In hexadecimal, `100f4` is the offset we need to encode. Convert `100f4` into binary:
```
100f4 = 0001 0000 0000 1111 0100 (16 bits).
```

Now, we need to split this immediate value into the parts that go into the `B-type` instruction format:
- **imm[12]**: The 12th bit is `0` (the most significant bit).
- **imm[10:5]**: The next 6 bits of the immediate are `000100`.
- **rs2**: `x0`, so `rs2 = 00000` (5 bits).
- **rs1**: `a5`, so `rs1 = 01111` (5 bits).
- **funct3**: `000` (3 bits for `beq`).
- **imm[4:1]**: The next 4 bits of the immediate are `1110`.
- **imm[11]**: The 11th bit of the immediate is `0`.

### Step 2: Final Instruction Encoding

Now, we can put all these fields together:

```
| imm[12] | imm[10:5] | rs2  | rs1   | funct3 | imm[4:1] | imm[11] | opcode |
|   0     | 000100    | 00000 | 01111 | 000    | 1110     | 0       | 1100011 |
```

This gives the following 32-bit binary instruction:

```
0 000100 00000 01111 000 1110 0 1100011
```

### Final 32-bit Machine Code:
Now, let's convert the binary encoding to hexadecimal:

```
0000 0000 0100 0000 0111 1000 0110 0011
```

This results in the machine code:

```
0x004f0033
```

### Conclusion:
The exact 32-bit instruction code for `beqz a5, 100f8` is **`0x004f0033`**.

<h3> 16) j 101b4 </h3>

The instruction `j 101b4` is a **J-type** instruction in RISC-V. The `j` instruction (Jump) is used to perform an unconditional jump to the target address. The target address is specified as an immediate value, and the jump is relative to the current Program Counter (PC).

### Breakdown of the `j 101b4` Instruction:
The `j` instruction is actually an alias for the `jal` (Jump and Link) instruction in RISC-V. When used with the `jal` opcode and `rd = x0`, the `jal` instruction just performs a jump without saving the return address.

Thus, `j 101b4` can be written as:
```
jal x0, 101b4
```
Where:
- **x0** is the destination register (which discards the return address, i.e., no link is saved).
- **101b4** is the target address offset.

### J-Type Instruction Format:
The `jal` instruction is a **J-type** instruction, with the following format:
```
imm[20] | imm[10:1] | imm[11] | imm[19:12] | rd | opcode
```

Where:
- **Opcode** for `jal` is `1101111` (7 bits).
- **rd** is the destination register, which is `x0` for `j`. So, `rd = 0` (5 bits).
- **Immediate** is a 20-bit signed value representing the offset to the target address. The immediate is computed as `target - (PC + 4)`. The immediate is divided into 4 parts:
  - `imm[20]`: The most significant bit.
  - `imm[10:1]`: The next 10 bits.
  - `imm[11]`: The next bit.
  - `imm[19:12]`: The least significant 8 bits.

### Step 1: Calculate the Immediate Offset

The target address for the jump is `101b4`. We need to calculate the offset relative to the current instruction. The offset is calculated as follows:
```
Immediate = target - (PC + 4)
```
Assuming the current instruction is at address `PC`, the next instruction will be at `PC + 4`. So the offset is:
```
101b4 - 4 = 101b0
```

In hexadecimal, `101b0` is the offset we need to encode. Convert `101b0` into binary:
```
101b0 = 0001 0000 0011 1011 0000 (20 bits).
```

### Step 2: Encode the Immediate Value
Now, we split this 20-bit immediate into the appropriate fields for a J-type instruction:
- **imm[20]**: The most significant bit is `0` (bit 20).
- **imm[10:1]**: The next 10 bits are `0000000011` (bits 10-1).
- **imm[11]**: The next bit is `0` (bit 11).
- **imm[19:12]**: The least significant 8 bits are `00011011` (bits 19-12).

### Step 3: Final Instruction Encoding

Now, we can put all the fields together:
```
| imm[20] | imm[10:1]  | imm[11] | imm[19:12] | rd   | opcode |
|   0     | 0000000011 |   0     | 00011011   | 00000 | 1101111 |
```

This gives the following 32-bit binary instruction:
```
0 0000000011 0 00011011 00000 1101111
```

### Final 32-bit Machine Code:
Now, convert the binary encoding into hexadecimal:
```
0000 0000 0011 0000 0110 1101 1000 0011
```

This results in the machine code:

```
0x00306f6f
```

### Conclusion:
The exact 32-bit instruction code for `j 101b4` is **`0x00306f6f`**.

<h3> 17) sub a2,a2,a0</h3>

The instruction `sub a2, a2, a0` is an **R-type** instruction in RISC-V. The `sub` instruction subtracts the value in register `a0` from the value in register `a2` and stores the result in register `a2`.

### Breakdown of the `sub` Instruction:

The `sub` instruction in RISC-V is an **R-type** instruction with the following format:
```
funct7 | rs2  | rs1  | funct3 | rd   | opcode
```

Where:
- **funct7** is a 7-bit field that specifies the operation. For `sub`, `funct7` is `0100000` (7 bits).
- **rs2** is the second source register, which is `a0`. In RISC-V, `a0` corresponds to register `x10`. So, `rs2 = 10`, which is `01010` in binary (5 bits).
- **rs1** is the first source register, which is `a2`. In RISC-V, `a2` corresponds to register `x12`. So, `rs1 = 12`, which is `01100` in binary (5 bits).
- **funct3** is the function code that specifies the specific type of operation. For `sub`, `funct3` is `000` (3 bits).
- **rd** is the destination register, which is `a2`. So, `rd = 12`, which is `01100` in binary (5 bits).
- **opcode** for all R-type instructions is `0110011` (7 bits).

### Final Instruction Encoding:

Now, let's combine all the fields together:

1. **funct7**: `0100000` (7 bits for `sub`).
2. **rs2**: `01010` (5 bits for `a0`).
3. **rs1**: `01100` (5 bits for `a2`).
4. **funct3**: `000` (3 bits for `sub`).
5. **rd**: `01100` (5 bits for `a2`).
6. **opcode**: `0110011` (7 bits for `R-type`).

### 32-bit Binary Instruction:

```
funct7 | rs2  | rs1  | funct3 | rd   | opcode
0100000 | 01010 | 01100 | 000   | 01100 | 0110011
```

This gives the following 32-bit binary instruction:

```
0100000 01010 01100 000 01100 0110011
```

### Convert to Hexadecimal:

Now, let's convert the binary encoding into hexadecimal:

```
0100 0000 0101 0001 1000 0011 0011
```

This results in the machine code:

```
0x40030333
```

### Conclusion:

The exact 32-bit instruction code for `sub a2, a2, a0` is **`0x40030333`**.

<h3> 18) lbu a5,1944(gp) </h3>

The instruction `lbu a5, 1944(gp)` is a **I-type** instruction in RISC-V, specifically a **Load Byte Unsigned** (`lbu`) instruction. This instruction loads a byte from memory into a register, using an immediate offset added to the value in a base register.

### Breakdown of the `lbu` Instruction:

The **`lbu`** (Load Byte Unsigned) instruction has the following format:
```
imm[11:0] | rs1  | funct3 | rd   | opcode
```

Where:
- **Opcode** for `lbu` is `0000011` (7 bits).
- **`rs1`** is the base register, which is `gp` (Global Pointer) in this case. In RISC-V, `gp` corresponds to register `x3`. So, `rs1 = 3`, which is `00011` in binary (5 bits).
- **`rd`** is the destination register, which is `a5`. In RISC-V, `a5` corresponds to register `x15`. So, `rd = 15`, which is `01111` in binary (5 bits).
- **Immediate** is the offset, which is `1944` in this case. The offset is encoded as a 12-bit signed immediate.

### Step 1: Immediate Value Encoding

The immediate value is `1944`. To represent it in 12 bits:
```
1944 (decimal) = 0x798 (hex) = 0000011110011000 (12 bits in binary)
```

### Step 2: Final Instruction Encoding

Now, we can assemble the 32-bit instruction. The instruction format is:

```
| imm[11:0] | rs1   | funct3 | rd    | opcode |
| 000001111001 | 00011 | 100    | 01111 | 0000011 |
```

Where:
- **imm[11:0]** is the 12-bit immediate (`000001111001`).
- **rs1** is `gp` (`00011`).
- **funct3** is `100` (for `lbu`).
- **rd** is `a5` (`01111`).
- **opcode** is `0000011` (for all load instructions).

### Step 3: Combine Fields

Combining all the fields together, we get the following 32-bit binary instruction:
```
000001111001 00011 100 01111 0000011
```

### Step 4: Convert to Hexadecimal

Now, let's convert the binary encoding to hexadecimal:

```
0000 0111 1001 0001 100 0111 0000 0110
```

This results in the machine code:

```
0x07930303
```

### Conclusion

The exact 32-bit instruction code for `lbu a5, 1944(gp)` is **`0x07930303`**.

<h3> 19) bnez a5,1018c </h3>

The instruction `bnez a5, 1018c` is a **B-type** instruction in RISC-V. The `bnez` instruction is a conditional branch that checks if the value in register `a5` is not equal to zero. If it is not zero, it will branch to the target address, specified by the immediate value.

### Breakdown of the `bnez a5, 1018c` Instruction:

The `bnez` instruction can be interpreted as:
```
bne a5, x0, 1018c
```
Which means "if the value in register `a5` is not equal to `0`, branch to the address `PC + 1018c`."

### B-Type Instruction Format:
The format for **B-type** instructions (like `bne`) is as follows:
```
imm[12] | imm[10:5] | rs2 | rs1 | funct3 | imm[4:1] | imm[11] | opcode
```

Where:
- **opcode** for all branch instructions is `1100011` (7 bits).
- **funct3** for `bne` is `001` (3 bits).
- **rs1** is the first source register (`a5` in this case), corresponding to register `x15`. So, `rs1 = 15`, which is `01111` in binary (5 bits).
- **rs2** is the second source register (`x0`), corresponding to register `x0`. So, `rs2 = 0`, which is `00000` in binary (5 bits).
- **Immediate** is the branch offset, calculated relative to the current PC. 

### Step 1: Calculate the Immediate Offset

The target address for the branch is `1018c`. We need to calculate the offset relative to the current instruction. The offset is calculated as:
```
Immediate = target - (PC + 4)
```

Assuming that the current instruction is at address `PC`, the next instruction will be at `PC + 4`. So the offset is:
```
1018c - 4 = 10188
```

In hexadecimal, `10188` is the offset we need to encode. Convert `10188` into binary:
```
10188 = 0001 0000 0001 1000 1000 (20 bits).
```

### Step 2: Encode the Immediate Value

Now, we split this 20-bit immediate into the appropriate parts for the B-type instruction:

- **imm[12]**: The 12th bit is `0` (most significant bit).
- **imm[10:5]**: The next 6 bits are `000100` (bits 10-5).
- **imm[11]**: The next bit is `0` (bit 11).
- **imm[4:1]**: The next 4 bits are `1000` (bits 4-1).
- **imm[11]**: The 11th bit of the immediate is `0`.

### Step 3: Final Instruction Encoding

Now, we can combine all the fields together:

```
| imm[12] | imm[10:5] | rs2  | rs1   | funct3 | imm[4:1] | imm[11] | opcode |
|    0    | 000100    | 00000 | 01111 | 001    | 1000     |    0    | 1100011 |
```

This gives the following 32-bit binary instruction:

```
0 000100 00000 01111 001 1000 0 1100011
```

### Final 32-bit Machine Code:

Converting the binary encoding to hexadecimal:

```
0000 0001 0000 0000 0111 1000 0011 0011
```

This results in the machine code:

```
0x010f0033
```

### Conclusion:

The exact 32-bit instruction code for `bnez a5, 1018c` is **`0x010f0033`**.


<h3> 20) addi gp,gp,-1780</h3>


The instruction `addi gp, gp, -1780` is an **I-type** instruction in RISC-V. The `addi` instruction performs an addition between a register and an immediate value, storing the result in a destination register.

### Breakdown of the `addi` Instruction:

The **`addi`** instruction format in RISC-V is:
```
imm[11:0] | rs1  | funct3 | rd   | opcode
```

Where:
- **Opcode** for `addi` is `0010011` (7 bits).
- **`rs1`** is the source register, which is `gp` (Global Pointer) in this case. In RISC-V, `gp` corresponds to register `x3`. So, `rs1 = 3`, which is `00011` in binary (5 bits).
- **`rd`** is the destination register, which is `gp` (`x3`). So, `rd = 3`, which is `00011` in binary (5 bits).
- **Immediate** is the signed 12-bit immediate value. In this case, the immediate value is `-1780`.

### Step 1: Convert the Immediate Value to Binary
The immediate value is `-1780`. To represent this value in 12 bits (as required by the `addi` instruction), we need to convert it to binary using two's complement.

First, convert `1780` to binary:
```
1780 = 0000011011111100 (binary)
```

Now, to represent `-1780` in two's complement:
- First, invert the bits:
```
1111100100000011
```
- Then, add 1:
```
1111100100000100
```

Thus, the 12-bit two's complement representation of `-1780` is:
```
1111100100000100
```

### Step 2: Assemble the Instruction

Now that we have the fields for the instruction, we can assemble the 32-bit instruction.

- **imm[11:0]** (12 bits): `111110010000` (for `-1780`).
- **rs1**: `gp`, which is register `x3`, so `00011` (5 bits).
- **funct3**: `000` (3 bits for `addi`).
- **rd**: `gp`, which is register `x3`, so `00011` (5 bits).
- **opcode**: `0010011` (7 bits for the `addi` instruction).

### Step 3: Final Instruction Encoding

Putting all the fields together:
```
imm[11:0] | rs1   | funct3 | rd    | opcode
111110010000 | 00011 | 000    | 00011 | 0010011
```

This results in the following 32-bit binary instruction:
```
111110010000 00011 000 00011 0010011
```

### Step 4: Convert to Hexadecimal

Now, let's convert the binary instruction to hexadecimal:
```
1111 1001 0000 0011 000 0001 1001 0011
```

This gives the machine code:
```
0xf9003033
```

### Conclusion

The exact 32-bit instruction code for `addi gp, gp, -1780` is **`0xf9003033`**.


</details>

<details>
  <summary> <h3> Task 4: </h3> By making use of RISCV Verilog Netlist and Testbench Perform the Simulation and Observe the Waveforms </summary>

  
</details>







