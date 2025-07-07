# 8-bit-cpu
<img src="Images/main_cpu.png">

# Capabilities
* Can store 256 lines of instructions and Data (Harvard Architecture)
* upto 128 Hz clock rate
* All arithematic and logical calculations

# Specifications
* 4 General purpose registers
* 256 Byte Ram
* 2 x 256 Byte ROM
* 8 bit Program counter
* 8 bit ALU
* 10 x 8 pixel display

## Component Breakdown

### 1. Program Counter (PC) and ROM

![Program Counter](Images/ROM_with_PC.png)
_The Program Counter module, In this cpu PC is a normal counter with counts up when Instructions is executed._

### 2. General Purpose Registers (GR)

![Instruction Register](Images/GP_registers.png)
_The General Purpose Register, holding temprary data for CPU to use._

### 3. ALU (Arithmetic Logic Unit)

![ALU](Images/4-bit_ALU.png)
_This is a 4-bit ALU based 74181IC. I have used two of these to make a 8-bit ALU._

<!-- ### 4. RAM Module

![RAM Module](Images/Ram.png)
_The RAM module for Temprary data storage and VRAM(data storage for display)._ -->

<!-- ### 5. Control Unit

![Control Unit](Images/Control_Unit.png)
_The Control Unit, This decodes instructions and sets the path for data to flow._ -->

---

## Schematics / Block Diagrams
(Link to or embed your schematics here)



