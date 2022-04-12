### Assembly language

####NASM assembler
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


