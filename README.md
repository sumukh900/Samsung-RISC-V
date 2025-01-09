# Samsung-RISC-V
The program is based on the RISC-V architecture and uses open-source tools to teach people about VLSI chip design and RISC-V. The instructor for this training is Kunal Ghosh Sir.
# Basic Details
**Name:** Sumukh Sharma

**College:** R V institute of technology and management

**Email ID:** sumukhguda@gmail.com

**GitHub Profile:** sumukh900

**LinkedIN Profile:** sumukh-guda

# VSDSquadron Mini Overview
<details>
<summary> Preview </summary>
<br>
  
## Block diagram of VSDSquadron Mini RISC-V development board is shown below

![b1](https://github.com/user-attachments/assets/e7339091-3882-4aa0-9fc5-665118aaa264)

## VSDSquadron Mini RISC-V development board Board image

![b2](https://github.com/user-attachments/assets/55c19e7e-ebfd-40cc-bf83-527ba790bb87)

## Information about the VSDSquadron Mini RISC-V SoC device

Refer to [CH32V003F4U6 RISC-V SoC Datasheet](https://www.vlsisystemdesign.com/wp-content/uploads/2024/01/Web01_CH32V003DS0.pdf) and [CH32V003F4U6 RISC-V SoC Reference Manual](https://www.vlsisystemdesign.com/wp-content/uploads/2023/09/Web02_CH32V003RM.PDF)

## Overview of VSDSquadron Mini RISC-V development boards

a) On-board 24MHz RC oscillator

b) 3 groups of GPIO ports, totaling 15 I/O ports

c)  USART, I2C, and SPI

d) UART implemented on USART

e) 2KB SRAM for volatile data storage, 16KB CodeFlash for program memory

f) On-board Programmer. NO NEED of any additional adapter

## Dimensions of the VSDSquadron Mini RISC-V development board

a) Form factor is 50.00 x 28.00 mm

b) Maximum height of the component at the top side: 8mm

c) Maximum height of the component at the bottom side: 1mm

</details>

# Installation of Virtual Box, openlane vdi file, VS Code setup

<details>
<summary> Preview </summary>
<br>
  
## Virtual Box and vsdsquadron vdi file setup screenshots

### For installing vdi file click [openlane_vdi_file](https://forgefunder.com/%7Ekunal/vsdsquadron.vdi)

![Screenshot 2025-01-08 232054](https://github.com/user-attachments/assets/962b47e0-375d-4f4a-b022-b38b54f0bfc7)

![Screenshot 2025-01-08 232115](https://github.com/user-attachments/assets/9ac864cb-1705-4275-84eb-3c03eb589d00)

![Screenshot 2025-01-09 104809](https://github.com/user-attachments/assets/6b06fdfe-9e83-458a-ac29-2a6d5e139105)

![Screenshot 2025-01-09 110020](https://github.com/user-attachments/assets/e5cd43b7-97f1-428b-a537-e0126b69c5c0)

</details>

# Task 1

<details>
<summary> C Based Lab Task </summary>
<br>
  
## Text editor view of sum1ton.c displaying the clean, commented source code with proper formatting and standard C library inclusion.

![Screenshot 2025-01-09 113819](https://github.com/user-attachments/assets/366f56e3-d7cf-47c5-aab6-5a0c91f41980)

## Terminal output showing multiple test runs of the program with different inputs (7, 8, 9) and their corresponding sum outputs (28, 36, 45), validating program functionality.

![Screenshot 2025-01-09 113757](https://github.com/user-attachments/assets/9b3cb810-7e07-4942-99be-4d8f31ada450)

</details>

<details>
<summary> Setting Up O1 and Ofast </summary>
<br>
  
## Source code of sum1ton.c showing the C implementation with basic loop structure to calculate cumulative sum, along with RISC-V compilation commands using different optimization flags.

![Screenshot 2025-01-09 155520](https://github.com/user-attachments/assets/294231dc-6cc3-48e7-a5dd-e97fe9626608)

</details>

<details>
<summary> RISC Based Lab Task </summary>
<br>
  
## Assembly code output showing the main function implementation with memory management, stack pointer adjustments, and function calls for printf and scanf operations also calculating the number of instructions used to implement the program using O1.

![Screenshot 2025-01-09 154246](https://github.com/user-attachments/assets/82d92c6f-f7da-4bb6-a13a-85b3d32a69c2)

## Assembly code output showing the main function implementation with memory management, stack pointer adjustments, and function calls for printf and scanf operations also calculating the number of instructions used to implement the program using Ofast.

![Screenshot 2025-01-09 154813](https://github.com/user-attachments/assets/1993d97b-1c4b-4811-a589-03049639d8ac)


