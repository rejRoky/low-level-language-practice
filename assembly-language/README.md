### Assembly language

#### NASM assembler
` whereis nasm `

#### Install  NASM in Linux 
` sudo apt install nasm `


#### Section

1. *** data *** (declaring initialized data or constants)
` section.data `
2. *** bss *** (used for declaring variables)
` section.bss `
3. *** text *** (used for keeping the actual code)
```
section.text
   global _start
_start:

```
#### Comments
` ; Comments in single line  `

#### Memory segments
1. *** Data segment *** (Declare of memory of .data ; .bss - Static memory for buffer)
2. *** Code segment ***  (.text section)
3. *** Stack ** *(Contains data values passed to functions and procedures) 

#### Registers
1. General registers
* Data registers 
* Pointer registers
* Index registers
2. Control registers
3. Segment registers


#### Data Registers
##### 32-bit data registers:  *** EAX, EBX, ECX, EDX ***
##### 16-bit data registers: *** AX, BX, CX, DX ***
##### 8-bit data registers: *** AH, AL, BH, BL, CH, CL, DH, DL ***

1. AX is the primary accumulator - input/output and most arithmetic instructions
2. BX is known as the base register - used in indexed addressing
3. CX is known as the count register - store the loop count in iterative operations
4. DX is known as the data register - used in input/output operations


#### Pointer registers
1. Instruction Pointer (IP) - stores the offset address of the next instruction to be executed
2. Stack Pointer (SP) - provides the offset value within the program stack
3. Base Pointer (BP) - mainly helps in referencing the parameter variables passed to a subroutine


#### Index registers
1. Source Index (SI) - used as source index for string operations
2. Destination Index (DI) - used as destination index for string operations

