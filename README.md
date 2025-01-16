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


                                

  R,I,S,B,U and J Instruction Types

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

RISC_V-objdump

![RISCV obj dump](https://github.com/user-attachments/assets/ecffa976-c761-4bb2-86eb-d5788698ea62)


Unique RISC_V Instructions

![Unique RISC_V Instructions](https://github.com/user-attachments/assets/10ab84b3-d696-48c2-9524-54fba381abb7)

32 Bit Instruction Code For Unique RISC_V Instructions

<h3>1. lui a2,0x376</h3>


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


<h3>2. lui a0,0x21</h3>

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


<h3>3. addi sp,sp,-16</h3>

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


<h3> 4. addi a2,a2,-256 </h3>


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

<h3> 5. li a1,10</h3>

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


<h3> 6. addi a0,a0,384</h3>


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


<h3> 7. sd ra,8(sp)</h3>


   





</details>







