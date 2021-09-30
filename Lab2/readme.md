## Executive Summary
null
## Hardware
### Hard Drives and Memory
#### Latency Vs. Transfer Rates
Latency has two distinct categories: seek time and rotational latency. Seek time is the time it takes to find the data physically on the disk. Rotational latency is the average time for a section of a disk to complete the seeking procedure. While latency is the delay while accessing data, transfer rates act as a cap on how much data can be transferred at once. 
#### Solid State Vs. Hard Drives
While hard drives use a physical disk to store data, solid state drives use Electronically Erasable Programmable Read Only Memory (EEPROM) to store data. Solid state is much faster than hard drives, but cost more. 
#### Random Access Memory
Increasing RAM makes the computer faster because RAM transfers data much faster than a hard disk, while also allowing the computer to multitask and store more data at the same time. Additionally, there are many differences between 32-bit and 64-bit systems. 32-bit systems are based on data 4 octets wide, while 64-bit system hosts 8 octets. These systems cannot be interchanged; a 32-bit OS will not run on a 64-bit CPU. 32-bit systems limit the RAM amount to around 3.2 GB, while 64-bit systems can use up to 17 billion GB of RAM. A 64-bit system is more efficient and secure than the 32-bit counterpart.
#### ALU and the Control Unit
The control unit acts as a leader inside the CPU and recieves orders from the RAM. It then breaks the instructions down for other components to follow. The Arithmetic Logic Unit (ALU) performs all the mathmatical procedures inside the CPU. The ALU performs the type of operation outputs an answer, or sends a flag to the control unit. The output goes to a register, which is like RAM in the way that it stores a number temporarily. The set wire from the control unit saves the value in the register. To access the number, the control unit activates an enable wire to tell the register to send a signal through the output wires of the register. These wires connect to the CPU bus, which is a group of wires that connect multiple components. There are many registers connected to the bus, and the control unit will turn on the register that it wants to save the value to. The control unit will then turn off the enable wire from the first register and turns off the bus. Due to the bus only being able to have one value on it at a time, the ALU uses a temporary register for another input. The instruction itself comes from an instruction register, and does not have an enable wire. The control unit will then tell the ALU what type of operation to perform. If the two inputs being compared, the ALU will send a flag to the control unit. If input A is larger, the "A is Larger" flag will be sent to the control unit. If the two units are equal, the "Equal" flag will be sent. Once the instruction is done, the output is saved into a flag register. The flag register outputs to the control unit. Once the comparison is done, the CPU enables the instruction address register, which tells the memory address that it is ready for the next instruction. This register automatically tell the RAM it is ready for the next instruction.
#### CPU, Input and Output
Pumping gas at the gas station is a good example of how input and output works in a CPU
#### Logic Gates and Circuits
null
#### IEEE
## Data Representation
### Decimal, Binary and Hexadecimal
null
### Hexadecimal Color Representation
null
## Conclusion
