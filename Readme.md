# This is my first repository

## Table of contents
* ![Day0](https://github.com/Parvin16/sd-training/blob/main/Readme.md#day-0)

## Day 0
### Topic - System/Tool Setup Check. GitHub ID creation

**Package** is a container that holds die and was connected to outside (external device) by using wire bonding.
Example of package - Quadruple in-line package (QIP) and Dual in-line package (DIP).

![die](https://user-images.githubusercontent.com/62828746/203833674-a44e1aa2-42f1-43eb-8890-016e0bc186e1.png)

* **Pad** - used to connect inside (core) to outside (I/O), good at ESD protection to prevent charge coming from outside damage the core inside.
* **Core** - consists of all the main logic gate (NMOS/PMOS) and cell block such as macro cell and foundry IP's.
* **I/O** - help in communication between die with external and will be connected to die by using wire bonding.

+ **Differences of macro vs foundry IP's**:

![note1day0](https://user-images.githubusercontent.com/118954022/204221744-4f6607e0-aa9f-415e-8d1a-8d6586602538.jpg)

  * **Macro** - a simple core/cell with simple functionality and can be easily found online.
  * **Foundry IP's** - cell with more specific functionality and the design was patent/owned by a company. Has higher value compared to macro.
  
==========================================================================================

How does a **software communicate with hardware**:

**Synthesis process** will help to convert software's instructions which is written in high level language to gate level language/machine language which is normally in binary format.

![software to hardware](https://user-images.githubusercontent.com/62828746/203840905-0b291241-5af6-40d1-9f6a-a8acb8176b7d.png)

**Synthesis process flow**:

1. **Specification/instructions** written in RTL (**high-level language** such as C, C++ or Java) as inputs.
1. **Compiler** will compile the instruction into **assembly language** (.exe).
1. **Assembler** will then convert **assembly language** into **gate level language** (low-level language.machine language) which is in binary format (operands), and it is the language understood by a computer.



### Lab 

![day0 lab vsd tarainig ](https://user-images.githubusercontent.com/118954022/204221523-4a01adeb-e998-4dc7-b023-e56e68c64cc9.jpg)




